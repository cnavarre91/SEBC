[root@ip-192-168-0-75 ~]# beeline
Beeline version 1.1.0-cdh5.10.0 by Apache Hive
beeline> !connect jdbc:hive2://ip-192-168-0-75.eu-west-1.compute.internal:10000/default;principal=hive/ip-192-168-0-75.eu-west-1.compute.internal@CNAVARRE.ES
scan complete in 2ms
Connecting to jdbc:hive2://ip-192-168-0-75.eu-west-1.compute.internal:10000/default;principal=hive/ip-192-168-0-75.eu-west-1.compute.internal@CNAVARRE.ES
Connected to: Apache Hive (version 1.1.0-cdh5.10.0)
Driver: Hive JDBC (version 1.1.0-cdh5.10.0)
Transaction isolation: TRANSACTION_REPEATABLE_READ
0: jdbc:hive2://ip-192-168-0-75.eu-west-1.com>
0: jdbc:hive2://ip-192-168-0-75.eu-west-1.com>
0: jdbc:hive2://ip-192-168-0-75.eu-west-1.com> SHOW TABLES;
INFO  : Compiling command(queryId=hive_20170320071313_f62a0a64-f68c-4a0c-8979-2ae62c76e701): SHOW TABLES
INFO  : Semantic Analysis Completed
INFO  : Returning Hive schema: Schema(fieldSchemas:[FieldSchema(name:tab_name, type:string, comment:from deserializer)], properties:null)
INFO  : EXPLAIN output for queryid hive_20170320071313_f62a0a64-f68c-4a0c-8979-2ae62c76e701 : ABSTRACT SYNTAX TREE:

TOK_SHOWTABLES


STAGE DEPENDENCIES:
  Stage-0 is a root stage [DDL]
  Stage-1 depends on stages: Stage-0 [FETCH]

STAGE PLANS:
  Stage: Stage-0
      Show Table Operator:
        Show Tables
          database name: default
          result file: file:/tmp/hive/000795c6-8cd6-4964-98d7-5c8840bd2b3a/hive_2017-03-20_07-13-51_703_3187824100429552793-1/-local-10000

  Stage: Stage-1
    Fetch Operator
      limit: -1
      Processor Tree:
        ListSink


INFO  : Completed compiling command(queryId=hive_20170320071313_f62a0a64-f68c-4a0c-8979-2ae62c76e701); Time taken: 0.698 seconds
INFO  : Executing command(queryId=hive_20170320071313_f62a0a64-f68c-4a0c-8979-2ae62c76e701): SHOW TABLES
INFO  : Starting task [Stage-0:DDL] in serial mode
INFO  : Completed executing command(queryId=hive_20170320071313_f62a0a64-f68c-4a0c-8979-2ae62c76e701); Time taken: 890.569 seconds
INFO  : OK
+-----------+--+
| tab_name  |
+-----------+--+
+-----------+--+
No rows selected (892.53 seconds)
