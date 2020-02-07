<h1> HADOOP	[Deployment]</h1>

HADOOP Ecosystem: [Cluster Storage, Process, Computations] : Uses for the Big-Data solution. Batch Interactive and Real-Time Data Access with Hadoop.
----------------------------------------------|

Big -Data : Term means when the volume & variant of data are not able to fit into any device or any tool does not able to get insight for output that time we say it big - data. That time we uses Tools that could handle it. Now a Days We are getting different shape & size of data and also we have different solutions in the market to deal with it.

<table>
  <tr>
    <th>Hadoop Framework</th>
    <th>Hadoop Components</th>
       <th>Description</th>
    </tr>
  <tr>
   <td ROWSPAN="1">Operating System</td>
  <td>Yarn</td>
  <td>Operating System for Hadoop(Hadoop Cluster Resource Management)</td>
  </tr>
  <tr>
   <td ROWSPAN="2">Data Storage</td>
  <td>HDFS</td>
    <td>Hadoop Distributed File System</td>
  </tr>
  <tr>
  <td>HBASE</td>
    <td>A columnar database that uses HDFS for its storage</td>
  </tr>

  <tr>  
   <td ROWSPAN="2">Visulization & UI Framework </td>
  <td>Hue</td>
  <td>A user and administrative interface that lets you browse HDFS files, run Pig and Hive queries and schedule workflows through Oozie</td>
  </tr>
   <tr>
     <td>HCATALOG</td>
    <td>A service that provides a relational view of data you store in HDFS</td>
  </tr>
  <tr>
   <td ROWSPAN="1">Job Scheduling</td>
  <td>OOZIE</td>
  <td>A job-scheduling tool</td>
  </tr>
  <tr>
  <td ROWSPAN="1">Coordinate the Work</td>  
  <td>ZooKEEPER</td>
       <td>A coordination service used by distributed applications such as Hadoop,HBase, Storm, Hive and Kafka</td>
  </tr>
  <tr>
   <td ROWSPAN="1">Security</td>
  <td>KERBEROS</td>
    <td>The Network authentication protocol.</td>
  </tr>
  <tr>
    <TD ROWSPAN="4">Data Manipulation</TD>
  <td>PIG</td>
    <td>A framework for analyzing large data sets that let you create data pipelines</td>
  </tr>
  <tr>
  <td>HIVE</td>
  <td>A distributed data warehouse for HDFS data that provides a SQL-like layer to this data</td>
  </tr>
  <tr>
  <td>IMPALA</td>
    <td>Its provide SQL-layer that reside on top of HDFS.</td>
  </tr>
   <td>AVRO</td>
   <td>Framework for transforming data into a compact binary format</td>
  </tr>
   <tr>
   <td ROWSPAN="3">Data Processing</td>  
  <td>Tez</td>
  <td>A data-processing framework for batch processing that also provides interactive querying capabilities</td>
  </tr>
   <tr>
  <td>Spark</td>
  <td>An object-relational mapping library that supports real-time stream processing</td>
   </tr>
  <td>Mapreduce</td>
  <td>MapReduce is a programming model and a framework for parallel data processing of large data sets.</td>
  </tr>
  <tr>
  <td ROWSPAN="4">Data Ingestion</td>
  <td>SQOOP</td>
  <td>A data movement tool that moves data between HDFS and relational databases</td>
   </tr>
  <tr>
  <td>Storm</td>
  <td>An object-relational mapping library that supports real-time stream processing</td>
   </tr>
  <tr>
  <td>FLUME</td>
    <td>Data-flow tool for moving streaming data into Hadoop</td>
  </tr>
  <tr>
  <td>KAFKA</td>
    <td>A message-queuing framework that handles large amounts of real-time data traffic</td>
   </tr>
</table>


## DEPLOYEMENT OF HADOOP ECOSYSTEM - "Documentation" :books:

<a href="https://github.com/CSiingh/Hadoop/tree/master/Deployment/Standalone" title="title"> Click **Standalone** :page_facing_up: </a>

Standalone: All Hadoop services run in a single JVM, and there are no daemons. In this mode, Hadoop uses the local file system and not
HDFS for storing its data, and MapReduce jobs run with a single mapper and a single reducer. This deployment model is best suited for developers to run their code.
Daemon is a UNIX or Linux long-running background process that answers requests for services

 #### Prerequisite Hardware
<table>
    <tr>
    <th>S.No</th>
     <th>OS</th>
     <th>Java</th>
     <th>Memory</th>
      <th>Hard Disk </th>
     </tr>
    <tr>
      <td>1</td>
      <td> Linux/ Unix</td>
      <td> Recommended Java version that match OS Version</td>
      <td> 512GB-2GB</td>
      <td> 1TB</td>
    </tr>
  </table>

[Click  **MultiNode** ](https://github.com/CSiingh/Hadoop/tree/master/Deployment/MultiNode) :page_facing_up:

All daemons (such as the DataNode, NameNode and ResourceManager processes) run on a single server. However, you can't use this in a real production environment — there is no way to configure data replication or high availability when all you have got is a single node!

 #### Prerequisite Hardware
<table>
    <tr>
    <th>S.No</th>
     <th>OS</th>
     <th>Java</th>
     <th>Memory</th>
      <th>Hard Disk </th>
     </tr>
    <tr>
      <td>1</td>
      <td> Linux/ Unix</td>
      <td> Recommended Java version that match OS Version</td>
      <td> 4GB-8GB  </td>
      <td> 1-4 TB</td>
    </tr>
  </table>
