```
[root@ip-172-31-17-107 ~]# beeline
Beeline version 1.1.0-cdh5.10.0 by Apache Hive
beeline> !connect jdbc:hive2://localhost:10000/default;principal=hive/ip-172-31-17-107.eu-west-1.compute.internal@CLOUDERA_KERBEROS
scan complete in 2ms
Connecting to jdbc:hive2://localhost:10000/default;principal=hive/ip-172-31-17-107.eu-west-1.compute.internal@CLOUDERA_KERBEROS
Connected to: Apache Hive (version 1.1.0-cdh5.10.0)
Driver: Hive JDBC (version 1.1.0-cdh5.10.0)
Transaction isolation: TRANSACTION_REPEATABLE_READ
0: jdbc:hive2://localhost:10000/default> SHOW TABLES;
INFO  : Compiling command(queryId=hive_20170309121111_c2ac8900-0473-47d2-bcc3-78c89e107925): SHOW TABLES
INFO  : Semantic Analysis Completed
INFO  : Returning Hive schema: Schema(fieldSchemas:[FieldSchema(name:tab_name, type:string, comment:from deserializer)], properties:null)
INFO  : Completed compiling command(queryId=hive_20170309121111_c2ac8900-0473-47d2-bcc3-78c89e107925); Time taken: 0.22 seconds
INFO  : Executing command(queryId=hive_20170309121111_c2ac8900-0473-47d2-bcc3-78c89e107925): SHOW TABLES
INFO  : Starting task [Stage-0:DDL] in serial mode
INFO  : Completed executing command(queryId=hive_20170309121111_c2ac8900-0473-47d2-bcc3-78c89e107925); Time taken: 0.355 seconds
INFO  : OK
+------------+--+
|  tab_name  |
+------------+--+
| customers  |
| sample_07  |
| sample_08  |
| web_logs   |
+------------+--+
4 rows selected (2.005 seconds)

```
