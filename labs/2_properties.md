```
[root@ip-172-31-33-253 ec2-user]# /usr/share/cmf/schema/scm_prepare_database.sh mysql scm scm scm_password -h 172.31.44.154
```
```
JAVA_HOME=/usr/java/jdk1.7.0_67-cloudera Verifying that we can write to /etc/cloudera-scm-server Creating SCM configuration file in /etc/cloudera-scm-server Executing: /usr/java/jdk1.7.0_67-cloudera/bin/java -cp /usr/share/java/mysql-connector-java.jar:/usr/share/java/oracle-connector-java.jar:/usr/share/cmf/schema/../lib/* com.cloudera.enterprise.dbutil.DbCommandExecutor /etc/cloudera-scm-server/db.properties com.cloudera.cmf.db. [ main] DbCommandExecutor INFO Successfully connected to database. All done, your SCM database is configured correctly!
```
```
[root@ip-172-31-47-253 cloudera-scm-server]# more db.properties
```
Content for `db.properties` is left out
