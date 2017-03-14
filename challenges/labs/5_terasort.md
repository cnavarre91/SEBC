[root@ip-192-168-0-125 ~]# time hadoop jar /opt/cloudera/parcels/CDH-5.10.0-1.cdh5.10.0.p0.41/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar terasort /user/neymar/tgen640_file /user/neymar/tsort640m
17/03/14 13:44:08 INFO terasort.TeraSort: starting
17/03/14 13:44:10 INFO hdfs.DFSClient: Created token for neymar: HDFS_DELEGATION_TOKEN owner=neymar@CNAVARRE.ES, renewer=yarn, realUser=, issueDate=1489513450501, maxDate=1490118250501, sequenceNumber=20, masterKeyId=8 on 192.168.0.125:8020
17/03/14 13:44:10 INFO security.TokenCache: Got dt for hdfs://ip-192-168-0-125.eu-west-1.compute.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 192.168.0.125:8020, Ident: (token for neymar: HDFS_DELEGATION_TOKEN owner=neymar@CNAVARRE.ES, renewer=yarn, realUser=, issueDate=1489513450501, maxDate=1490118250501, sequenceNumber=20, masterKeyId=8)
17/03/14 13:44:10 INFO input.FileInputFormat: Total input paths to process : 2
Spent 432ms computing base-splits.
Spent 6ms computing TeraScheduler splits.
Computing input splits took 439ms
Sampling 10 splits of 392
Making 8 from 100000 sampled records
Computing parititions took 2148ms
Spent 2589ms computing partitions.
17/03/14 13:44:12 INFO client.RMProxy: Connecting to ResourceManager at ip-192-168-0-125.eu-west-1.compute.internal/192.168.0.125:8032
17/03/14 13:44:13 INFO mapreduce.JobSubmitter: number of splits:392
17/03/14 13:44:13 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1489509798627_0007
17/03/14 13:44:13 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 192.168.0.125:8020, Ident: (token for neymar: HDFS_DELEGATION_TOKEN owner=neymar@CNAVARRE.ES, renewer=yarn, realUser=, issueDate=1489513450501, maxDate=1490118250501, sequenceNumber=20, masterKeyId=8)
17/03/14 13:44:13 INFO impl.YarnClientImpl: Submitted application application_1489509798627_0007
17/03/14 13:44:13 INFO mapreduce.Job: The url to track the job: http://ip-192-168-0-125.eu-west-1.compute.internal:8088/proxy/application_1489509798627_0007/
17/03/14 13:44:13 INFO mapreduce.Job: Running job: job_1489509798627_0007
17/03/14 13:44:22 INFO mapreduce.Job: Job job_1489509798627_0007 running in uber mode : false
17/03/14 13:44:22 INFO mapreduce.Job:  map 0% reduce 0%
17/03/14 13:44:32 INFO mapreduce.Job:  map 1% reduce 0%
17/03/14 13:44:40 INFO mapreduce.Job:  map 3% reduce 0%
17/03/14 13:44:42 INFO mapreduce.Job:  map 4% reduce 0%
17/03/14 13:44:51 INFO mapreduce.Job:  map 5% reduce 0%
17/03/14 13:44:52 INFO mapreduce.Job:  map 6% reduce 0%
17/03/14 13:45:00 INFO mapreduce.Job:  map 7% reduce 0%
17/03/14 13:45:04 INFO mapreduce.Job:  map 8% reduce 0%
17/03/14 13:45:05 INFO mapreduce.Job:  map 9% reduce 0%
17/03/14 13:45:09 INFO mapreduce.Job:  map 10% reduce 0%
17/03/14 13:45:15 INFO mapreduce.Job:  map 11% reduce 0%
17/03/14 13:45:17 INFO mapreduce.Job:  map 12% reduce 0%
17/03/14 13:45:18 INFO mapreduce.Job:  map 13% reduce 0%
17/03/14 13:45:27 INFO mapreduce.Job:  map 14% reduce 0%
17/03/14 13:45:28 INFO mapreduce.Job:  map 15% reduce 0%
17/03/14 13:45:29 INFO mapreduce.Job:  map 16% reduce 0%
17/03/14 13:45:37 INFO mapreduce.Job:  map 17% reduce 0%
17/03/14 13:45:39 INFO mapreduce.Job:  map 18% reduce 0%
17/03/14 13:45:44 INFO mapreduce.Job:  map 19% reduce 0%
17/03/14 13:45:48 INFO mapreduce.Job:  map 20% reduce 0%
17/03/14 13:45:52 INFO mapreduce.Job:  map 21% reduce 0%
17/03/14 13:45:55 INFO mapreduce.Job:  map 22% reduce 0%
17/03/14 13:46:00 INFO mapreduce.Job:  map 23% reduce 0%
17/03/14 13:46:03 INFO mapreduce.Job:  map 24% reduce 0%
17/03/14 13:46:04 INFO mapreduce.Job:  map 25% reduce 0%
17/03/14 13:46:12 INFO mapreduce.Job:  map 26% reduce 0%
17/03/14 13:46:13 INFO mapreduce.Job:  map 27% reduce 0%
17/03/14 13:46:16 INFO mapreduce.Job:  map 28% reduce 0%
17/03/14 13:46:22 INFO mapreduce.Job:  map 29% reduce 0%
17/03/14 13:46:26 INFO mapreduce.Job:  map 30% reduce 0%
17/03/14 13:46:28 INFO mapreduce.Job:  map 31% reduce 0%
17/03/14 13:46:33 INFO mapreduce.Job:  map 32% reduce 0%
17/03/14 13:46:38 INFO mapreduce.Job:  map 33% reduce 0%
17/03/14 13:46:40 INFO mapreduce.Job:  map 34% reduce 0%
17/03/14 13:46:45 INFO mapreduce.Job:  map 35% reduce 0%
17/03/14 13:46:49 INFO mapreduce.Job:  map 36% reduce 0%
17/03/14 13:46:50 INFO mapreduce.Job:  map 37% reduce 0%
17/03/14 13:46:57 INFO mapreduce.Job:  map 38% reduce 0%
17/03/14 13:46:58 INFO mapreduce.Job:  map 39% reduce 0%
17/03/14 13:47:02 INFO mapreduce.Job:  map 40% reduce 0%
17/03/14 13:47:07 INFO mapreduce.Job:  map 41% reduce 0%
17/03/14 13:47:09 INFO mapreduce.Job:  map 42% reduce 0%
17/03/14 13:47:14 INFO mapreduce.Job:  map 43% reduce 0%
17/03/14 13:47:17 INFO mapreduce.Job:  map 44% reduce 0%
17/03/14 13:47:21 INFO mapreduce.Job:  map 45% reduce 0%
17/03/14 13:47:26 INFO mapreduce.Job:  map 46% reduce 0%
17/03/14 13:47:31 INFO mapreduce.Job:  map 47% reduce 0%
17/03/14 13:47:35 INFO mapreduce.Job:  map 48% reduce 0%
17/03/14 13:47:36 INFO mapreduce.Job:  map 49% reduce 0%
17/03/14 13:47:42 INFO mapreduce.Job:  map 50% reduce 0%
17/03/14 13:47:44 INFO mapreduce.Job:  map 51% reduce 0%
17/03/14 13:47:47 INFO mapreduce.Job:  map 52% reduce 0%
17/03/14 13:47:53 INFO mapreduce.Job:  map 54% reduce 0%
17/03/14 13:47:59 INFO mapreduce.Job:  map 55% reduce 0%
17/03/14 13:48:02 INFO mapreduce.Job:  map 56% reduce 0%
17/03/14 13:48:05 INFO mapreduce.Job:  map 57% reduce 0%
17/03/14 13:48:12 INFO mapreduce.Job:  map 58% reduce 0%
17/03/14 13:48:13 INFO mapreduce.Job:  map 59% reduce 0%
17/03/14 13:48:20 INFO mapreduce.Job:  map 60% reduce 0%
17/03/14 13:48:21 INFO mapreduce.Job:  map 61% reduce 0%
17/03/14 13:48:26 INFO mapreduce.Job:  map 62% reduce 0%
17/03/14 13:48:30 INFO mapreduce.Job:  map 63% reduce 0%
17/03/14 13:48:32 INFO mapreduce.Job:  map 64% reduce 0%
17/03/14 13:48:38 INFO mapreduce.Job:  map 65% reduce 0%
17/03/14 13:48:39 INFO mapreduce.Job:  map 66% reduce 0%
17/03/14 13:48:46 INFO mapreduce.Job:  map 67% reduce 0%
17/03/14 13:48:48 INFO mapreduce.Job:  map 68% reduce 0%
17/03/14 13:48:50 INFO mapreduce.Job:  map 69% reduce 0%
17/03/14 13:48:57 INFO mapreduce.Job:  map 70% reduce 0%
17/03/14 13:48:59 INFO mapreduce.Job:  map 71% reduce 0%
17/03/14 13:49:03 INFO mapreduce.Job:  map 72% reduce 0%
17/03/14 13:49:07 INFO mapreduce.Job:  map 73% reduce 0%
17/03/14 13:49:11 INFO mapreduce.Job:  map 74% reduce 0%
17/03/14 13:49:15 INFO mapreduce.Job:  map 75% reduce 0%
17/03/14 13:49:16 INFO mapreduce.Job:  map 76% reduce 0%
17/03/14 13:49:22 INFO mapreduce.Job:  map 77% reduce 0%
17/03/14 13:49:24 INFO mapreduce.Job:  map 78% reduce 0%
17/03/14 13:49:30 INFO mapreduce.Job:  map 79% reduce 0%
17/03/14 13:49:33 INFO mapreduce.Job:  map 80% reduce 0%
17/03/14 13:49:34 INFO mapreduce.Job:  map 81% reduce 0%
17/03/14 13:49:43 INFO mapreduce.Job:  map 82% reduce 0%
17/03/14 13:49:44 INFO mapreduce.Job:  map 83% reduce 0%
17/03/14 13:49:48 INFO mapreduce.Job:  map 84% reduce 0%
17/03/14 13:49:57 INFO mapreduce.Job:  map 85% reduce 4%
17/03/14 13:50:01 INFO mapreduce.Job:  map 85% reduce 7%
17/03/14 13:50:02 INFO mapreduce.Job:  map 85% reduce 14%
17/03/14 13:50:03 INFO mapreduce.Job:  map 85% reduce 18%
17/03/14 13:50:07 INFO mapreduce.Job:  map 86% reduce 18%
17/03/14 13:50:09 INFO mapreduce.Job:  map 87% reduce 18%
17/03/14 13:50:16 INFO mapreduce.Job:  map 88% reduce 18%
17/03/14 13:50:23 INFO mapreduce.Job:  map 89% reduce 18%
17/03/14 13:50:25 INFO mapreduce.Job:  map 90% reduce 18%
17/03/14 13:50:26 INFO mapreduce.Job:  map 90% reduce 19%
17/03/14 13:50:34 INFO mapreduce.Job:  map 91% reduce 19%
17/03/14 13:50:42 INFO mapreduce.Job:  map 92% reduce 19%
17/03/14 13:50:43 INFO mapreduce.Job:  map 93% reduce 19%
17/03/14 13:50:52 INFO mapreduce.Job:  map 94% reduce 19%
17/03/14 13:50:56 INFO mapreduce.Job:  map 94% reduce 20%
17/03/14 13:51:00 INFO mapreduce.Job:  map 95% reduce 20%
17/03/14 13:51:01 INFO mapreduce.Job:  map 96% reduce 20%
17/03/14 13:51:09 INFO mapreduce.Job:  map 97% reduce 20%
17/03/14 13:51:17 INFO mapreduce.Job:  map 98% reduce 20%
17/03/14 13:51:19 INFO mapreduce.Job:  map 99% reduce 20%
17/03/14 13:51:20 INFO mapreduce.Job:  map 99% reduce 21%
17/03/14 13:51:26 INFO mapreduce.Job:  map 100% reduce 21%
17/03/14 13:51:28 INFO mapreduce.Job:  map 100% reduce 23%
17/03/14 13:51:31 INFO mapreduce.Job:  map 100% reduce 28%
17/03/14 13:51:32 INFO mapreduce.Job:  map 100% reduce 42%
17/03/14 13:51:34 INFO mapreduce.Job:  map 100% reduce 44%
17/03/14 13:51:37 INFO mapreduce.Job:  map 100% reduce 47%
17/03/14 13:51:39 INFO mapreduce.Job:  map 100% reduce 57%
17/03/14 13:51:40 INFO mapreduce.Job:  map 100% reduce 64%
17/03/14 13:51:41 INFO mapreduce.Job:  map 100% reduce 66%
17/03/14 13:51:44 INFO mapreduce.Job:  map 100% reduce 67%
17/03/14 13:51:45 INFO mapreduce.Job:  map 100% reduce 81%
17/03/14 13:51:46 INFO mapreduce.Job:  map 100% reduce 86%
17/03/14 13:51:49 INFO mapreduce.Job:  map 100% reduce 88%
17/03/14 13:51:51 INFO mapreduce.Job:  map 100% reduce 95%
17/03/14 13:51:54 INFO mapreduce.Job:  map 100% reduce 97%
17/03/14 13:51:57 INFO mapreduce.Job:  map 100% reduce 100%
17/03/14 13:51:58 INFO mapreduce.Job: Job job_1489509798627_0007 completed successfully
17/03/14 13:51:58 INFO mapreduce.Job: Counters: 49
        File System Counters
                FILE: Number of bytes read=2906953865
                FILE: Number of bytes written=5800901182
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=6553661936
                HDFS: Number of bytes written=6553600000
                HDFS: Number of read operations=1200
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=16
        Job Counters
                Launched map tasks=392
                Launched reduce tasks=8
                Data-local map tasks=392
                Total time spent by all maps in occupied slots (ms)=3632648
                Total time spent by all reduces in occupied slots (ms)=694116
                Total time spent by all map tasks (ms)=3632648
                Total time spent by all reduce tasks (ms)=694116
                Total vcore-seconds taken by all map tasks=3632648
                Total vcore-seconds taken by all reduce tasks=694116
                Total megabyte-seconds taken by all map tasks=3719831552
                Total megabyte-seconds taken by all reduce tasks=710774784
        Map-Reduce Framework
                Map input records=65536000
                Map output records=65536000
                Map output bytes=6684672000
                Map output materialized bytes=2843137011
                Input split bytes=61936
                Combine input records=0
                Combine output records=0
                Reduce input groups=65536000
                Reduce shuffle bytes=2843137011
                Reduce input records=65536000
                Reduce output records=65536000
                Spilled Records=131072000
                Shuffled Maps =3136
                Failed Shuffles=0
                Merged Map outputs=3136
                GC time elapsed (ms)=52730
                CPU time spent (ms)=1484830
                Physical memory (bytes) snapshot=199892717568
                Virtual memory (bytes) snapshot=631835029504
                Total committed heap usage (bytes)=224434585600
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=6553600000
        File Output Format Counters
                Bytes Written=6553600000
17/03/14 13:51:58 INFO terasort.TeraSort: done

real    7m50.344s
user    0m11.175s
sys     0m0.425s
