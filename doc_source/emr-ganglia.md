# Ganglia<a name="emr-ganglia"></a>

The Ganglia open source project is a scalable, distributed system designed to monitor clusters and grids while minimizing the impact on their performance\. When you enable Ganglia on your cluster, you can generate reports and view the performance of the cluster as a whole, as well as inspect the performance of individual node instances\. Ganglia is also configured to ingest and visualize Hadoop and Spark metrics\. For more information about the Ganglia open\-source project, go to [http://ganglia\.info/](http://ganglia.info/)\. 

When you view the Ganglia web UI in a browser, you see an overview of the cluster's performance, with graphs detailing the load, memory usage, CPU utilization, and network traffic of the cluster\. Below the cluster statistics are graphs for each individual server in the cluster\. 

The following table lists the version of Ganglia included in the latest release of the Amazon EMR 6\.x series, along with the components that Amazon EMR installs with Ganglia\.

For the version of components installed with Ganglia in this release, see [Release 6\.5\.0 Component Versions](emr-650-release.md)\.


**Ganglia version information for emr\-6\.5\.0**  

| Amazon EMR Release Label | Ganglia Version | Components Installed With Ganglia | 
| --- | --- | --- | 
| emr\-6\.5\.0 | Ganglia 3\.7\.2 | emrfs, emr\-goodies, ganglia\-monitor, ganglia\-metadata\-collector, ganglia\-web, hadoop\-client, hadoop\-hdfs\-datanode, hadoop\-hdfs\-library, hadoop\-hdfs\-namenode, hadoop\-kms\-server, hadoop\-yarn\-nodemanager, hadoop\-yarn\-resourcemanager, hadoop\-yarn\-timeline\-server, webserver | 

The following table lists the version of Ganglia included in the latest release of the Amazon EMR 5\.x series, along with the components that Amazon EMR installs with Ganglia\.

For the version of components installed with Ganglia in this release, see [Release 5\.34\.0 Component Versions](emr-5340-release.md)\.


**Ganglia version information for emr\-5\.34\.0**  

| Amazon EMR Release Label | Ganglia Version | Components Installed With Ganglia | 
| --- | --- | --- | 
| emr\-5\.34\.0 | Ganglia 3\.7\.2 | emrfs, emr\-goodies, ganglia\-monitor, ganglia\-metadata\-collector, ganglia\-web, hadoop\-client, hadoop\-hdfs\-datanode, hadoop\-hdfs\-library, hadoop\-hdfs\-namenode, hadoop\-kms\-server, hadoop\-yarn\-nodemanager, hadoop\-yarn\-resourcemanager, hadoop\-yarn\-timeline\-server, webserver | 

**Topics**
+ [Create a cluster with Ganglia](init_Ganglia.md)
+ [View Ganglia metrics](view_Ganglia.md)
+ [Hadoop and Spark metrics in Ganglia](Hadoopmetrics_Ganglia.md)
+ [Ganglia release history](Ganglia-release-history.md)