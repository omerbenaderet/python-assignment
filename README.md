Hi there!  
This script is converting a CSV file containing logs to a new CSV file with the parsed log data splitted to fields: Timestamp, Service, Organization, Status and Duration. It will save the new CSV file as "Parsed-Logs.xlsx" in the local directory.  
In addition, it will print the analyzed data of each organization-service pair: the average duration of successfull runs and the average time between successfull runs.  
Bonus :  
You can improve the service/insfrastructure by using autoscaler that will scale up in case of high workload and scale back down, or based on historical data, predict the use of resources and scale resources dynamically based on anticipated workload patterns. In Addition, you can use caching mechanisms to store and retrieve frequently used data.  
Additional logs and metrics that will help you monitor better:  
- Performance metrics of resources and throughtput.  
- Error rate and detailed log error messages.  
- Response time and service availability metrics to track user experience.
