
ip-172-31-44-154.us-west-2.compute.internal

[root@ip-172-31-44-154 ec2-user]# mysql -u root -pcloudera -e "status";
Warning: Using a password on the command line interface can be insecure.
--------------
mysql  Ver 14.14 Distrib 5.6.38, for Linux (x86_64) using  EditLine wrapper

Connection id:          14
Current database:
Current user:           root@localhost
SSL:                    Not in use
Current pager:          stdout
Using outfile:          ''
Using delimiter:        ;
Server version:         5.6.38 MySQL Community Server (GPL)
Protocol version:       10
Connection:             Localhost via UNIX socket
Server characterset:    latin1
Db     characterset:    latin1
Client characterset:    utf8
Conn.  characterset:    utf8
UNIX socket:            /var/lib/mysql/mysql.sock
Uptime:                 6 min 49 sec

Threads: 1  Questions: 58  Slow queries: 0  Opens: 67  Flush tables: 1  Open tables: 60  Queries per second avg: 0.141
--------------


[root@ip-172-31-44-154 ec2-user]# mysql -u root -pcloudera -e show databases;
Warning: Using a password on the command line interface can be insecure.
ERROR 1049 (42000): Unknown database 'databases'
[root@ip-172-31-44-154 ec2-user]# mysql -u root -pcloudera -e "show databases";
Warning: Using a password on the command line interface can be insecure.
+--------------------+
| Database           |
+--------------------+
| information_schema |
| hive               |
| hue                |
| mysql              |
| oozie              |
| performance_schema |
| rman               |
| scm                |
| sentry             |
+--------------------+
