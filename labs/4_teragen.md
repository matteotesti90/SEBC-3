Command invocation is missing
```
[reilly@ip-172-31-33-253 ~]$ hdfs dfs -ls /user/reilly/tgen 
Found 13 items
-rw-r--r-- 3 reilly reilly 0 2017-11-03 06:05 /user/reilly/tgen/_SUCCESS
-rw-r--r-- 3 reilly reilly 546133400 2017-11-03 06:06 /user/reilly/tgen/part-m-00000
-rw-r--r-- 3 reilly reilly 546133300 2017-11-03 06:06 /user/reilly/tgen/part-m-00001
-rw-r--r-- 3 reilly reilly 546133300 2017-11-03 06:06 /user/reilly/tgen/part-m-00002
-rw-r--r-- 3 reilly reilly 546133400 2017-11-03 06:06 /user/reilly/tgen/part-m-00003
-rw-r--r-- 3 reilly reilly 546133300 2017-11-03 06:06 /user/reilly/tgen/part-m-00004
-rw-r--r-- 3 reilly reilly 546133300 2017-11-03 06:06 /user/reilly/tgen/part-m-00005
-rw-r--r-- 3 reilly reilly 546133400 2017-11-03 06:06 /user/reilly/tgen/part-m-00006
-rw-r--r-- 3 reilly reilly 546133300 2017-11-03 06:07 /user/reilly/tgen/part-m-00007
-rw-r--r-- 3 reilly reilly 546133300 2017-11-03 06:06 /user/reilly/tgen/part-m-00008
-rw-r--r-- 3 reilly reilly 546133400 2017-11-03 06:06 /user/reilly/tgen/part-m-00009
-rw-r--r-- 3 reilly reilly 546133300 2017-11-03 06:06 /user/reilly/tgen/part-m-00010
-rw-r--r-- 3 reilly reilly 546133300 2017-11-03 06:06 /user/reilly/tgen/part-m-00011
```
```
[reilly@ip-172-31-33-253 ~]$ hadoop fsck -blocks /user/reilly/tgen DEPRECATED: Use of this script to execute hdfs command is deprecated. Instead use the hdfs command for it.
Connecting to namenode via http://ip-172-31-44-154.eu-central-1.compute.internal:50070 FSCK started by reilly (auth:SIMPLE) from /172-31-44-154 for path /user/reilly/tgen at Fri Nov 03 06:08:56 EDT 2017 .............
Status: HEALTHY 
Total size: 6553600000 B 
Total dirs: 1 Total files: 13 
Total symlinks: 0 
Total blocks (validated): 204 (avg. block size 32125490 B) 
Minimally replicated blocks: 204 (100.0 %) 
Over-replicated blocks: 0 (0.0 %) 
Under-replicated blocks: 0 (0.0 %) 
Mis-replicated blocks: 0 (0.0 %) 
Default replication factor: 3 
Average block replication: 3.0 
Corrupt blocks: 0 
Missing replicas: 0 (0.0 %) 
Number of data-nodes: 5
Number of racks: 1 FSCK ended at Fri Nov 03 06:07:01 EDT 2017 in 10 milliseconds

The filesystem under path '/user/reilly/tgen' is HEALTHY
```
