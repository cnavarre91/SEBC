Teragen command:
  #time hadoop jar /opt/cloudera/parcels/CDH-5.10.0-1.cdh5.10.0.p0.41/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar teragen -D dfs.block.size=33554432 10485760 /user/cnavarre91/10GB_File

Execution time Teragen command:
real    0m15.259s
user    0m22.400s
sys     0m1.356s


Terasort command:
 #time hadoop jar /opt/cloudera/parcels/CDH-5.10.0-1.cdh5.10.0.p0.41/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar terasort /user/cnavarre91/10GB_File /user/cnavarre91/10GB_FileX

Execution time Terasort command:
real    1m8.145s
user    1m13.498s
sys     0m5.640s

