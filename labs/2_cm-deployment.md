```
[root@ip-172-31-33-253 ec2-user]# curl -u admin:admin "http://172.31.33.253:7180/api/v9/cm/deployment"
{
  "timestamp" : "2017-11-03T10:07:30.199Z",
  "clusters" : [ {
    "name" : "cluster",
    "displayName" : "Cluster 1",
    "version" : "CDH5",
    "fullVersion" : "5.0.0",
    "services" : [ ],
    "parcels" : [ {
      "product" : "CDH",
      "version" : "5.11.2-1.cdh5.11.2.p0.4",
      "stage" : "DISTRIBUTED",
      "clusterRef" : {
        "clusterName" : "cluster"
      }
    } ]
  } ],
  "hosts" : [ {
    "hostId" : "6eb3475d-5c28-47fe-bd02-97bbac9c4ff7",
    "ipAddress" : "172.31.33.180",
    "hostname" : "ip-172-31-33-180.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "c48b6be6-569a-4ab8-b022-d8342def7683",
    "ipAddress" : "172.31.33.253",
    "hostname" : "ip-172-31-33-253.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "d42668b7-3f2d-41a1-bda9-fcb59965c7c2",
    "ipAddress" : "172.31.36.202",
    "hostname" : "ip-172-31-36-202.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "089ed3da-0aa8-4f15-8a5e-0eb53fa9dc49",
    "ipAddress" : "172.31.44.154",
    "hostname" : "ip-172-31-44-154.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "113fa38d-2ccb-4def-89a9-c1263e9932c1",
    "ipAddress" : "172.31.47.205",
    "hostname" : "ip-172-31-47-205.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  } ],
  "users" : [ {
    "name" : "admin",
    "roles" : [ "ROLE_ADMIN" ],
    "pwHash" : "24ddbd848b4a5249ba2b1187caf6c56af7fd78ee01f62507fcd2af023e3af6bf",
    "pwSalt" : 6340318826306870538,
    "pwLogin" : true
  } ],
  "versionInfo" : {
    "version" : "5.11.2",
    "buildUser" : "jenkins",
    "buildTimestamp" : "20170811-0014",
    "gitHash" : "3c3ea33a12076fb83a8f11c4452c52fac685d01b",
    "snapshot" : false
  },
  "managerSettings" : {
    "items" : [ {
      "name" : "CLUSTER_STATS_START",
      "value" : "10/28/2012 1:40"
    }, {
      "name" : "PUBLIC_CLOUD_STATUS",
      "value" : "ON_PUBLIC_CLOUD"
    }, {
      "name" : "REMOTE_PARCEL_REPO_URLS",
      "value" : "https://archive.cloudera.com/cdh5/parcels/{latest_supported}/,https://archive.cloudera.com/cdh4/parcels/latest/,https://archive.cloudera.com/impala/parcels/latest/,https://archive.cloudera.com/search/parcels/latest/,https://archive.cloudera.com/accumulo/parcels/1.4/,https://archive.cloudera.com/accumulo-c5/parcels/latest/,https://archive.cloudera.com/kafka/parcels/latest/,https://archive.cloudera.com/navigator-keytrustee5/parcels/latest/,http://archive.cloudera.com/kudu/parcels/latest/,https://archive.cloudera.com/spark/parcels/latest/,https://archive.cloudera.com/sqoop-connectors/parcels/latest/"
    } ]
  },
  "allHostsConfig" : {
    "items" : [ ]
  },
  "peers" : [ ],
  "hostTemplates" : {
    "items" : [ ]
  }
```
