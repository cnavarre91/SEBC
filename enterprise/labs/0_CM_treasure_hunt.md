1 -What is ubertask optimization?

Ubertask: certain 'small tasks' suc as ==> 
"By default a job that has less than 10 mappers only and one reducer, and the input size is less than the size of one HDFS block is said to be small job. 
This small job hadoop will consider as Uber task. So the hadoop job will significantly run faster for 'small' jobs also."

2 -Where in CM is the Kerberos Security Realm value displayed?

Administration > Settings > Kerberos Security Realm field


3 -Which CDH service(s) host a property for enabling Kerberos authentication?
All the CDH have this property 
HDFS 		
Hive 		
Hue 		
Oozie 		
Solr 		
Spark 	
YARN (MR2 Included) 		
ZooKeeper


4 -How do you upgrade the CM agents?
  1-Stop Services and Roles
  2-Stop Cloudera Manager Server, Database, and Agent
  
5 -Give the tsquery statement used to chart Hue's CPU utilization?
   #select cpu_system_rate + cpu_user_rate where category=ROLE and serviceName="hue"
   
6 -Name all the roles that make up the Hive service
 Gateway 
 Hive Metastore Server Default Group
 HiveServer2
 WebHCat Server
 
