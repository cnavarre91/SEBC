Teragen command:
 time hadoop jar /opt/cloudera/parcels/CDH-5.10.0-1.cdh5.10.0.p0.41/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar teragen -D dfs.block.size=33554432 16777216 /user/neymar/tgen640^C

Result of time:
        real    0m35.146s
        user    0m5.766s
        sys     0m0.246s

[hdfs@ip-192-168-0-127 ~]$ hdfs dfs -ls /user/neymar/tgen640
Found 3 items
-rw-r--r--   3 hdfs supergroup          0 2017-03-10 06:18 /user/neymar/tgen640/_SUCCESS
-rw-r--r--   3 hdfs supergroup  838860800 2017-03-10 06:18 /user/neymar/tgen640/part-m-00000
-rw-r--r--   3 hdfs supergroup  838860800 2017-03-10 06:18 /user/neymar/tgen640/part-m-00001
