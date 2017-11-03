[root@ip-172-31-33-253 jdk1.7.0_67-cloudera]# hdfs dfs -ls /user
Found 9 items
drwxr-xr-x   - admin    admin               0 2017-11-03 05:48 /user/admin
drwxr-xr-x   - frankola frankola            0 2017-11-03 05:49 /user/frankola
drwxr-xr-x   - hdfs     supergroup          0 2017-11-03 05:48 /user/hdfs
drwxrwxrwx   - mapred   hadoop              0 2017-11-03 05:43 /user/history
drwxrwxr-t   - hive     hive                0 2017-11-03 05:45 /user/hive
drwxrwxr-x   - hue      hue                 0 2017-11-03 05:45 /user/hue
drwxrwxr-x   - oozie    oozie               0 2017-11-03 05:46 /user/oozie
drwxr-xr-x   - reilly   reilly              0 2017-11-03 05:49 /user/reilly
drwxr-x--x   - spark    spark               0 2017-11-03 05:44 /user/spark


[root@ip-172-31-33-253 jdk1.7.0_67-cloudera]# beeline -u jdbc:hive2://ip-172-31-44-154.eu-central-1.compute.internal:10000
scan complete in 2ms
Connecting to jdbc:hive2://ip-172-31-44-154.eu-central-1.compute.internal:10000
Connected to: Apache Hive (version 1.1.0-cdh5.8.5)
Driver: Hive JDBC (version 1.1.0-cdh5.8.5)
Transaction isolation: TRANSACTION_REPEATABLE_READ
Beeline version 1.1.0-cdh5.8.5 by Apache Hive
0: jdbc:hive2://ip-172-31-44-154.eu-central-1> show tables;
INFO  : Compiling command(queryId=hive_20171103055858_6f199fc4-29a3-4088-897b-f7b7b3f4d690): show tables
INFO  : Semantic Analysis Completed
INFO  : Returning Hive schema: Schema(fieldSchemas:[FieldSchema(name:tab_name, type:string, comment:from deserializer)], properties:null)
INFO  : Completed compiling command(queryId=hive_20171103055858_6f199fc4-29a3-4088-897b-f7b7b3f4d690); Time taken: 0.007 seconds
INFO  : Executing command(queryId=hive_20171103055858_6f199fc4-29a3-4088-897b-f7b7b3f4d690): show tables
INFO  : Starting task [Stage-0:DDL] in serial mode
INFO  : Completed executing command(queryId=hive_20171103055858_6f199fc4-29a3-4088-897b-f7b7b3f4d690); Time taken: 0.041 seconds
INFO  : OK
+------------+--+
|  tab_name  |
+------------+--+
| customers  |
| sample_07  |
| sample_08  |
| web_logs   |
+------------+--+
4 rows selected (0.173 seconds)
