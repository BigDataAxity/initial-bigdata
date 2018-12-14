# initial-bigdata
Lista de frameworks, software, librerías y recursos de Big Data


## Frameworks, Distributed Programming and Data processing:
* [Apache Hadoop](http://hadoop.apache.org/) - distributed processing of large data sets across clusters. Include HDFS, YARN and MapReduce.
* [Apache MapReduce](https://hadoop.apache.org/docs/r1.2.1/mapred_tutorial.html) - process vast amounts of data in-parallel on large clusters.
* [Apache Tez](https://es.hortonworks.com/apache/tez/) - extensible framework for building high performance batch that accelerated Hadoop Query Processing, coordinated by YARN.
* [Apache Beam](https://beam.apache.org/) - define and execute data processing workflows.
* [Apache Spark](http://spark.apache.org/) - batch processing. Combine SQL, streaming, and complex analytics (SQL, Streaming, MLlib, GraphX)


## Data Platform distribution:
* [Hortonoworks](https://www.hortonworks.com/) - provides a Sandbox that can help you get started learning, developing and testing features about HDF. 
* [Cloudera](https://www.cloudera.com/) - provides a VMs that make it easy to quickly self-learning purposes. Also includes a tutorial, sample data, and scripts for getting started.  


## User Interface:
* [Hadoop User Interface (HUE)](http://gethue.com/) - web application for interacting with Hadoop by Cloudera.
* [Ambari](https://ambari.apache.org/) - software for provisioning, managing, and monitoring Hadoop clusters by Hortonworks.


## Cluster manager
* [Apache YARN](https://hortonworks.com/apache/yarn/) - architectural center of Hadoop that allows multiple data processing engines.
* [Apache Mesos](http://mesos.apache.org/) - kernel cluster administrator. 


## Data Ingestion:
* [Kakfa](http://kafka.apache.org/) - a high throughput published subscribed messaging system.
* [Flume](http://flume.apache.org/) - collects and aggregates log data.


## Stream Processing:
* [Apache Spark Streaming](http://spark.apache.org/docs/0.7.3/streaming-programming-guide.html) - extension of the core Spark API that enables scalable, high-throughput, fault-tolerant stream processing.
* [Apache Flink](https://flink.apache.org/) - fault-tolerant, high-performance runtime and automatic program optimization over unbounded and bounded data streams.
* [Apache Storm](http://storm.apache.org/) - makes it easy to reliably process unbounded streams of data.
* [Apache Samza](http://samza.apache.org/) - allows you to build stateful applications that process data in real-time from multiple sources including Kafka, run on YARN. 


## SQL Processing
* [Apache Hive](http://hive.apache.org/) - data warehouse software using SQL for Hadoop.
* [Impala](https://www.cloudera.com/products/open-source/apache-hadoop/impala.html) - massively parallel SQL engine on Hadoop. Cloudera's alternative to Hive.


## External Data Storage - NoSQL:
  * #### Key Map Data Model
      * [HBase](http://hbase.apache.org/) - column-oriented distributed datastore, inspired by BigTable.
      * [Accumulo](https://accumulo.apache.org/) - distributed key/value store, inspired by BigTable. Offer better security model.
      * [Cassandra](http://cassandra.apache.org/) - column-oriented distributed datastore, inspired by BigTable.
      * [Redis](https://redis.io/) - distributed in-memory data structure store, used as a database, cache and message broker.
      * [Google BigTable]() - 


## Document Data Model
* [JSON](https://www.json.org/)
* [MongoDB](https://www.mongodb.com/) - collection of documents.


## Scripting:
* [Apache Pig](https://pig.apache.org/) - is a high-level platform for creating MapReduce programs that run on Hadoop.


## Query Engine:
* [Apache Drill](http://drill.apache.org/) - schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage.
* [Apache Phoenix](http://phoenix.apache.org/index.html) - massively parallel, relational database engine supporting OLTP for Hadoop using Apache HBase as its backing store.
* [Presto](https://prestodb.io/) - distributed SQL query engine for running interactive analytic queries.


## Coordinator:
* [Apache Zookeeper](http://zookeeper.apache.org/) - is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.


## Workflow Scheduler:
* [Oozie](http://oozie.apache.org/) - workflow scheduler system to manage Apache Hadoop jobs, Directed Acyclical Graphs (DAGs) of actions.


## Data Visualization:
* [Apache Zeppeling](https://zeppelin.apache.org/) - web-based notebook that enables data-driven, interactive data analytics and collaborative documents with SQL, Scala and more.
