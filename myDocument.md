Basic analysis of given data: 
       Job ID and salary range is having integer values
       Remaining all fields havin string values. 
As initial step found some duplicate.
       count before remove duplicate **2946**
       count after removed duplicate **2915**
 

 In this notebook , we have 2 set of code. by appling all logic and finally given complete code which is suitable for deployment.

 Deployment method as below:
 *****************************

 1. spark-submit:
      * package this code as .py file and run through spark-submit command with cluster mode or client mode (if local).
      * In automated mode, the spark-submit code can be scheduled in control-m or any scheduling tool.

2. cloud deployent.
    * This can be done through AWS or GCB. Using emr add-steps

3. If any tool like dataiku having jupiter node , this code can be run in production and can see the results. 

    