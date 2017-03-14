Teragen command:
time hadoop jar /opt/cloudera/parcels/CDH-5.10.0-1.cdh5.10.0.p0.41/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar teragen -D dfs.block.size=16777216 65536000 /user/neymar/tgen640_file



Result of time:

real    1m56.240s
user    0m6.624s
sys     0m0.267s


[hdfs@ip-192-168-0-127 ~]$ hdfs dfs -ls /user/neymar/tgen640_file
Found 3 items
-rw-r--r--   3 neymar supergroup          0 2017-03-14 13:40 /user/neymar/tgen640_file/_SUCCESS
-rw-r--r--   3 neymar supergroup 3276800000 2017-03-14 13:40 /user/neymar/tgen640_file/part-m-00000
-rw-r--r--   3 neymar supergroup 3276800000 2017-03-14 13:40 /user/neymar/tgen640_file/part-m-00001
