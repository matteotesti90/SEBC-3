```
[root@ip-172-31-33-253 ec2-user]# tail -f /var/log/cloudera-scm-server/cloudera-scm-server.log
2017-11-03 05:56:58,537 INFO main:com.cloudera.cmon.components.CsdMetricSchemaGenerator: Loading monitoring definitions from KAFKA-5.11.2
2017-11-03 05:56:58,537 INFO main:com.cloudera.cmon.components.CsdMetricSchemaGenerator: Loading monitoring definitions from HDFS-5.11.2
2017-11-03 05:56:58,538 INFO main:com.cloudera.cmon.components.CsdMetricSchemaGenerator: Loading monitoring definitions from /mgmt.mdl
2017-11-03 05:56:58,538 INFO main:com.cloudera.cmon.components.CsdMetricSchemaGenerator: Loading monitoring definitions from /mdls/cdh5/oozie.mdl
2017-11-03 05:56:58,659 WARN main:com.cloudera.cmon.components.CsdMetricSchemaGenerator: CSD metric kudu_data_dirs_full contains conflicting numerator values. Skipping metric definition.
2017-11-03 05:56:58,930 INFO main:com.cloudera.cmon.components.MetricSchemaUpdate: persisting 5271 new metrics
2017-11-03 05:57:01,267 INFO main:com.cloudera.cmon.components.MetricSchemaUpdate: persisting 0 updated metrics
2017-11-03 05:57:01,268 INFO main:com.cloudera.cmon.components.MetricSchemaManager: CSD metrics processed.
2017-11-03 05:57:01,268 INFO main:com.cloudera.cmon.components.MetricSchemaManager: Registering cross entity aggregates...
2017-11-03 05:57:03,611 INFO main:com.cloudera.cmon.components.MetricSchemaUpdate: persisting 21212 new metrics
2017-11-03 05:57:06,438 INFO main:com.cloudera.cmon.components.MetricSchemaUpdate: persisting 0 updated metrics
2017-11-03 05:57:06,442 INFO main:com.cloudera.cmon.components.MetricSchemaManager: Cross entity aggregates processed.
2017-11-03 05:57:08,897 INFO JvmPauseMonitor:com.cloudera.enterprise.debug.JvmPauseMonitor: Detected pause in JVM or host machine (e.g. a stop the world GC, or JVM not scheduled): paused approximately 1011ms: GC pool 'ParNew' had collection(s): count=5 time=86ms, GC pool 'ConcurrentMarkSweep' had collection(s): count=1 time=1226ms
2017-11-03 05:57:09,089 INFO main:com.cloudera.cmon.MetricSchema: Setting current metrics schema to 7YHfETHjpz-oiE5a-63xvTaHVZ0
```
@mfernest: Initial line of the log file is left out
@mfernest: Line showing "Jetty server started" is left out
