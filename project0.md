#####1010data
It provides a cloud-based software platform along with big data discovery and analytics service for both business and technical clients.  
The cloud-based big data discovery leads a new generation solution. This new solution has significant superiorities in the performance, scalability and data sharing. It enables more convenient data governance through centralized management of data and analytics. Furthermore, this solution enables collaboration both within and beyond the enterprise with the feature data monetization.  
######Weakness:
As one of the cloud computing services, there should be concerns about the security and privacy in the cloud in the cloud-based software platform. Another problem is the so called vendor-lock-in. Since it is difficult when the customer wants to switch to a new provider. Transferring huge data from the old one to a new one is painful. There is implicit dependency on the provider. So clients should be careful when picking a vendor.   
######Reference:
White paper: "Data Discovery Meets Big Data in the Cloud, moving from conventional to next-generation data discovery"
https://www.1010data.com/  
http://www.javacodegeeks.com/2013/04/advantages-and-disadvantages-of-cloud-computing-cloud-computing-pros-and-cons.html, Ilias Tsagklis, Advantages and Disadvantages of Cloud Computing – Cloud computing pros and cons  

#####Accumulo
Apache Accumulo provides secure data delivery for government applications. It is a secure distributed NoSQL database based on Google's Big Table design and is built on top of Apache Hadoop, Zookeeper, and Thrift.   
There are some advantages of it like Scale-out architecture, security, full consistency, high availability, automatic sharding and server-side programming. Among them, the cell-level security and server-side programming are the most outstanding two features. The former one allows us to store data with different security requirement in the same table. People can only see the data which they are authorized. The latter one enables us to perform additional processing on key/value pairs locally in order to reduce the data movement system.  
######Reference:
http://www.cloudera.com/content/cloudera/en/products-and-services/cdh/accumulo.html  
https://accumulo.apache.org/  

#####Actian Ingres 
It is a relational database whose main clients are enterprises. It is able to reduce IT costs and time-to-value. 
The latest version enables the internationalization of customer applications. It also enhances the performance and reduces the configuration overhead. Another key feature is that it supports the out-of-the-box spatial management. That is, Actian Ingres uses a file-based approach to remove the barriers for managing spatial data types. Users are able to manage spatial data as part of a transaction and develop applications on the platform to share data in spatial cases.  
######Weakness:
There is a discussion about the lock related issues users have in Ingres when using a thread going on Database. There is a separate set of limits for row locks.   
######Reference:
http://www.actian.com/products/operational-databases/ingres/  

#####Actian Matrix
It is great at dealing with massive data, many users and significant analytic complexity.  
Strengths:  
Its key benefits included fast analytic, massive scalability, easy integration and flexible deployment options with its massively parallel processing architecture.
Weaknesses:  
However, it is not necessary to use Actian Matrix for smaller data analysis.   
Reference:  
http://wwwcdn.actian.com/wp-content/uploads/2014/06/DS06-ActianMatrix.pdf  

Actian PSQL  
It is perfect as a solution for packaged business applications. The updated version brings critical new features: Online Defragmentation, VM live migration support, improved Unicode support and an updated PSQL installer.   
The key benefits of PSQL: we can use it for large database with less cost. Besides, it has siganificant stability and reliability.   
References:  
http://www.actian.com/products/operational-databases/psql/  

Actian Vector  
It is a database good for BI users who want faster answers. It needs less hardware and virtually no database tuning. Thus its benefits are to deliver faster reporting and analytics as well as less cost and less effort needs.  
There are also restrictions:  
The amount of data stored in Actian Vector is limited. The number of concurrent sessions active in the database cannot be more than 5. Users can run an Actian DataFlow job on up to 10 nodes in a cluster. It is not re-distributable in any way to a third-party.   
References:  
http://www.actian.com/wp-content/uploads/2014/07/Actian-Analytics-Platform-Express-FAQ.pdf  
http://www.ticout.com/descargas/Actian-Vector-Datasheet.pdf  

Actian Versant  
The Versant Object Database enables software developers to deal with large-scale database requirements for extremely complicated object models easily. The main benefit of it comes into play when the object model becomes more complex that we cannot deal with it relational database system. While the Versant Object Database can easily handle growth in enterprise object models – access time to objects is constant, independent of the inheritance structure.   
References:  
http://www.actian.com/products/operational-databases/versant/  
http://www.actian.com/products/operational-databases/  
http://www.actian.com/wp-content/uploads/2014/01/Actian-Object-Database-8.0-Datasheet.pdf  

ADABAS  
The Adabas database management system can manage data without limits and leverage your data to meet constantly changing business demands. It has benefits like fast data processing, appliable to many platforms and easy integration.  
Weakness:  
Since NATURAL is an interpreted language, for big batch processing you might experience some performance issues.   
Interaction with storage and MVS data areas is not straightforward.   
The communication with some other languages is somewhat poor.  
Reference:  
http://www.softwareag.com/corporate/products/adabas_natural/adabas/overview/default.asp  
http://ibmmainframes.com/about15310.html  

Aerospike:  
It is a distributed, scalable NoSQL database. It has three key features: a flexible, scalable platform; the robustness and reliability and operational efficiency.  
One disadvantages of Aerospoke in running in asynchronous mode is the potential for data loss on node outages. This can mean data inconsistency in the case of a transient failure   
Reference:  
http://www.odbms.org/wp-content/uploads/2013/11/NoSQL-Failover.pdf  
http://www.aerospike.com/docs/architecture/  

AffinityDB
AffinityNG is a universal embedded platform for information processing, control and communication, with a graph database at its heart.
The strengths of Affinity are designed to lower the barrier of entry for systems targeting the Internet of Things (IoT), Wireless Sensor Networks (WSNs), ubiquitous computing, control systems and robotics. It also maximizes the efficiency of writing, executing, tuning and maintaining applications for those contexts.
Reference:
http://pc1664.pharmazie.uni-marburg.de/affinity/

Allegrograph
It is a graph-database that can store anything in the subject, predicate, object and graph fields of its triples. It can be both more flexible and faster than RDBMSs. Besides, AllegroGraph has the ability to encode values directly into its triples.
Weakness:
First, the exact kind of reasoning used is not clear from outside. It could be anything from simple lookup to complex description logic reasoning. And second, the bar that inventors have set for hardware usage is pretty high.
References:
http://franz.com/agraph/cresources/white_papers/Master-Thesis_Neuenstadt.pdf
http://franz.com/agraph/support/documentation/current/agraph-introduction.html#header3-46

Altibase HDB
It is an in-memory database with hybrid architecture. It is also a single database that delivers high-intensity data processing through the In-Memory database portion and large storage capacity through the on-disk database portion. 
However, it has drawbacks in flexibility, strict durability and blazing speed.
References:
http://altibase.com/in-memory-database-hybrid-products/how-to-choose-between-in-memory-database-or-hybrid-database/
http://altibase.com/in-memory-database-hybrid-products/hdbtm-hybrid-dbms/

Altibase XDB 
It is the world’s fastest In-Memory only database with direct attach mode (DCI mode) to eliminate overhead. Another advantage of it is the unmatched product maturity and long history of enterprise experience. It has rich set of tools and utilities and supported several operating systems.
Reference:
http://altibase.com/in-memory-database-hybrid-products/xdb/#toggle-id-2

Altiscale
This company developed a purpose-built, petabyte-scale infrastructure delivering Apache Hadoop as a cloud service. Altiscale’s optimized solution is faster, more reliable, easier to use, and more flexible than alternatives. 
Reference:
https://www.altiscale.com/hadoop-as-a-service/

Apache Drill
Apache Drill provides direct queries on self-describing and semi-structured data in files (such as JSON, Parquet) and HBase tables without needing to define and maintain schemas in a centralized store such as Hive metastore. 
With Drill, businesses can minimize switching costs and learning curves for users with the familiar ANSI SQL syntax. Users can also plug-and-play with Hive environments to enable ad-hoc low latency queries on existing Hive tables and reuse Hive's metadata, hundreds of file formats and UDFs out of the box.
Reference:
https://bigdatanerd.wordpress.com/2013/11/19/war-on-sql-over-hadoop/
http://drill.apache.org/

Apache Hive
The Apache Hive data warehouse software supports querying and managing large datasets residing in distributed storage. Hive provides a mechanism to project structure onto this data and query the data using a SQL-like language called HiveQL. At the same time this language also allows traditional map/reduce programmers to plug in their custom mappers and reducers when it is inconvenient or inefficient to express this logic in HiveQL.
However, since it is using MapReduce, it has  all the drawbacks which MapReduce has. Such as expensive shuffle phase as well as huge IO operations. Besides, Hive still not support multiple reducers that make queries slower.
Reference:
https://bigdatanerd.wordpress.com/2013/11/19/war-on-sql-over-hadoop/
https://hive.apache.org/

Apache S4
S4 is a general-purpose, distributed, scalable, fault-tolerant, pluggable platform that allows programmers to easily develop applications for processing continuous unbounded streams of data.
Performance evauation according to the experimental results. Yahoo! S4 distributes the events unequally which leadsto more resource consumption on some nodes than others. The fault tolerance is not up to the expectation. The network is used heavily in Yahoo! S4 and the availability can be an issue for high network bandwidth demanding applications. 
Reference:
http://incubator.apache.org/s4/
Jagmohan Chauhan, Shaiful Alam Chowdhury and Dwight Makaroff, Performance Evaluation of Yahoo! S4: A First Look, Department of Computer Science, University of Saskatchewan.

Apache storm
Storm is a distributed real time computation system. Similar to how Hadoop provides a set of general primitives for doing batch processing, Storm provides a set of general primitives for doing real-time computation. Storm is simple, can be used with any programming language, is used by many companies, and is a lot of fun to use!
Apache Storm is a free and open source distributed real-time computation system. Storm makes it easy to reliably process unbounded streams of data, doing for real-time processing what Hadoop did for batch processing. Storm is simple, can be used with any programming language, and is a lot of fun to use!
Storm has many use cases: real-time analytics, online machine learning, continuous computation, distributed RPC, ETL, and more. Storm is fast: a benchmark clocked it at over a million tuples processed per second per node. It is scalable, fault-tolerant, guarantees your data will be processed, and is easy to set up and operate.
Storm is a good choice if you need sub-second latency and no data loss. Spark Streaming is better if you need stateful computation, with the guarantee that each event is processed exactly once. Spark Streaming programming logic may also be easier because it is similar to batch programming, in that you are working with batches (albeit very small ones).
Reference:
http://xinhstechblog.blogspot.com/2014/06/storm-vs-spark-streaming-side-by-side.html

Apache Tajo
Apache Tajo is a robust big data relational and distributed data warehouse system for Apache Hadoop. Tajo is designed for low-latency and scalable ad-hoc queries, online aggregation, and ETL (extract-transform-load process) on large-data sets stored on HDFS (Hadoop Distributed File System) and other data sources. By supporting SQL standards and leveraging advanced database techniques, Tajo allows direct control of distributed execution and data flow across a variety of query evaluation strategies and optimization opportunities.
Reference:
http://tajo.apache.org/

ArangoDB
It is a distributed free and open-source database with a flexible data model for documents, graphs and key-values. It has hgih performance and its query language is convenient and simple to use.
Weakness:
One limit is that the implementation is not optimized for very long-running or very voluminous operations, and may not be usable for these cases.
Another is that a transaction operation information must fit into main memory.
Ongoing transactions will also prevent the write-ahead logs from being fully garbage-collected. 
Reference:
https://www.arangodb.com/
https://docs.arangodb.com/Transactions/Limitations.html

Attivio
Active intelligence engine provides power innovation across the enterprise with the Big Data Search and Dexterity platform that’s built for change. 
Strengths:
Immediate Visibility Into All Information and universal contextual enrichment. Besides, Attivio delivers all the information you need by connecting directly to any source while enforcing standards for performance, governance & usability.
Reference:
http://kentico.attivio.com/SiteMedia/Attivio/Active_Security_Technical_Brief.pdf

AWS DynamoDB
Amazon DynamoDB is a fast and flexible NoSQL database service. It is a fully managed database and supports both document and key-value data models. It has benefits as flexible data model, reliability, and high performance. And it is a great fit for mobile, web, gaming, ad-tech, IoT, and many other applications.
Limits:
The base API for DynamoDB (even if your project uses the Java SDK) is a JSON HTTP interface. So there is the overhead of de/serializing JSON and making a HTTP request. 
Design Limitations: Placing large data sets underneath any given hash key means that a client application has to sort through all of the data for a hash key to find a needed record. Besides, the use of local secondary indices brings the limitation on the amount of data associated with any given hash key in the system.
It could bring performance issue. The application which frequently updates or inserts records under the same hash key can lead to poor performance.
Reference:
On the use of AWS DynamoDB, http://codinginthetrenches.com/2014/06/07/on-the-use-of-aws-dynamodb/
http://aws.amazon.com/dynamodb/

AWS Elaticache
It is a web service that makes it easy to deploy and run Memcached or Redis protocol-compliant server nodes in the cloud. It has benefits as improving the performance of web applications by allowing you to retrieve information from a fast, managed, in-memory caching system. The service simplifies and offloads the management, monitoring and operation of in-memory cache environments. However, using Amazon ElastiCache, users can not only improve load and response times to user actions and queries.
Reference:
Redis – a popular open-source in-memory key-value store that supports data structures such as sorted sets and lists. 
http://aws.amazon.com/elasticache/faqs/

AWS EMR
Amazon Elastic MapReduce (Amazon EMR) is a web service that makes it easy to quickly and cost-effectively process vast amounts of data. It uses Hadoop, an open source framework, to distribute user's data and processing across a resizable cluster of Amazon EC2 instances. It can also run other distributed frameworks such as Spark and Presto.
Reference:
http://aws.amazon.com/elasticmapreduce/

Amazon Kinesis
It is a fully managed, cloud-based service for real-time processing of large, distributed data streams. With Amazon Kinesis Client Library (KCL), we can build Amazon Kinesis Applications and use streaming data to power real-time dashboards, generate alerts, and implement dynamic pricing and advertising, and more. Kinesis, however, does not support to move data from where they originate (often outside of AWS) into AWS. 
Reference:
http://www.quora.com/What-can-you-do-with-Amazon-Kinesis

AWS RDS
Amazon Relational Database Service (Amazon RDS) is a web service that makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while managing time-consuming database management tasks, freeing you up to focus on your applications and business.
It has limitations for each AWS account per region, on the number of Amazon RDS resources that can be created. There are also naming constraints in Amazon RDS. Besides， Amazon RDS instances can support files with a maximum size of 2TB due to underlying file system constraints.
Reference
http://aws.amazon.com/rds/
http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html
http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Limits.html

AWS Redshift
Amazon Redshift is a fast, fully managed, petabyte-scale data warehouse service that makes it simple and cost-effective to efficiently analyze all your data using your existing business intelligence tools. It is optimized for datasets ranging from a few hundred gigabytes to a petabyte or more with affordable costs.
Limitations:
Amazon Redshift has quotas that limit the number of clusters users can create, the total number of nodes that you can provision, and the number of snapshots that you can create; these quotas are per AWS account per region. In addition to quotas, Amazon Redshift has limits for the number of nodes that user can allocate per cluster, the number of user-defined databases, the number of schemas you can create per database is 256, the number of concurrent user connections that can be made to a cluster, the number of AWS accounts authorized to restore a snapshot, the maximum size of a single row loaded by using the COPY command. 
Reference:
http://aws.amazon.com/documentation/redshift/
http://docs.aws.amazon.com/redshift/latest/mgmt/amazon-redshift-limits.html


AWS SimpleDB
Amazon SimpleDB is a highly available and flexible non-relational data store that offloads the work of database administration. 
It has a 1000 bytes limitation per attribute value, which is not enough in lots of cases. Then, the maximum domain size is 10GB. 
Reference:
http://aws.amazon.com/simpledb/
http://stackoverflow.com/questions/648270/whats-the-point-of-using-amazon-simpledb

Azure DocumentDB
DocumentDB is a NoSQL document database service designed for modern mobile and web applications. DocumentDB delivers consistently fast reads and writes, schema flexibility, and the ability to easily scale a database up and down on demand.
It has following key benefits: Ad hoc queries with familiar SQL syntax, JavaScript execution within the database, fully managed, elastically scalable throughput and storage.
Reference:
http://azure.microsoft.com/en-us/documentation/articles/documentdb-introduction/

Azure search:
It provides search-as-a-service for web and mobile app development. The benefits as following: reliable performance, easily tune search indices, scalability, sophisticated search functionality, quick get up and running, simple search index management.
However, Microsoft Azure is not mature in our opinion, good for labs, training. SQL Azure only implements a subset of T-SQL. Its report also costs extra. Also there may be data charges.
Reference:
http://azure.microsoft.com/en-us/services/search/
http://searchsqlserver.techtarget.com/feature/Why-you-should-think-twice-about-Windows-Azure-SQL-Database

Azure SQL database
It is a relational database-as-a-service that makes tier-1 capabilities easily accessible. It has following benefits: scalable to thousands of databases, predictable performance you can dial up or down, availability-backed by replicas & uptime SLA, data protection via auditing, restore & geo-replication, programmatic DBA-like functionality for efficient DevOps, self-managed for near-zero maintenance. 
However, it has limitations regarding security. The Microsoft Azure SQL Database service is only available through TCP port 1433. All communications between Microsoft Azure SQL Database and user's application require encryption (SSL) at all times. Microsoft Azure SQL Database supports only SQL Server Authentication.
Reference:
https://msdn.microsoft.com/en-us/library/azure/ff394108.aspx
http://azure.microsoft.com/en-us/services/sql-database/

Berkeley DB
Oracle Berkeley DB provides the best open source embeddable databases allowing developers the choice of various Object storage for their data model. Its key advantages: eliminating overhead while providing the flexibility to tailor the database to your requirements, lower total cost of ownership with lower implementation and administration costs and lower licensing and hardware costs.
Disadvantages:
BDB is not the ideal database management system for applications requiring a variety of different services.
Reference
http://www.oracle.com/us/products/database/berkeley-db/overview/index.html
http://www.databaseskill.com/449542/

BigCache
BigCache is a very simple cache API providing users with an infinite shared cache backed by Amazon S3.
Reference
https://code.google.com/p/bigcache/

BitYota
It provides data warehouse as a service. It is able to load and analyze fast changing data from multiple sources. BitYota has advantages as following: no need for data transformation, get insights in minutes, real-time data feeds for fast analytics.
Reference
http://www.bityota.com/product/

Cassandra
Cassandra is a NoSQL Column family implementation supporting the Big Table data model using the architectural aspects introduced by Amazon Dynamo. Some of the strong points of Cassandra are highly scalable and highly available with no single point of failure. It has very high write throughput, good read throughput and flexible schema.
Disadvantages:
It does not support ACID transactions. Cassandra does not support foreign keys, so it is not possible for Cassandra to manage the data consistency on a user's behalf. Cassandra does not support atomic operations. Searching is not built into the core of the Cassandra architecture. Besides, If a node in a Cassandra cluster has failed, the cluster will continue to work if you have replicas.
Reference
http://www.ibm.com/developerworks/library/os-apache-cassandra/

CitusDB:
CitusDB scales out PostgreSQL through sharding and replication. Its powerful query engine parallelizes SQL queries over very large datasets and enables real-time responses. 
Reference
http://www.citusdata.com/

ClearDB
ClearDB is a powerful, fault-tolerant database-as-a-service in the cloud for users' MySQL powered applications. It is great for developers and quick and easy to setup. Besides, it is able to minimize database failures.
Reference
http://azure.microsoft.com/en-us/marketplace/partners/cleardb-mysql-database/cleardb-mysql-database/

Cloudant
It is a distributed database-as-a-service for web & mobile apps. It mostly focuses on building and improving their products, instead of worrying about scaling and managing databases on their own.
Reference
http://stackshare.io/stackups/cloudant-vs-amazon-simpledb-vs-amazon-dynamodb

Cloudera
Cloudera Inc. is a software company that provides Apache Hadoop-based software, support and services, and training to business customers. Hadoop is designed to make storing and processing large amounts of data affordable.
Apache Hadoop has weakness as follows:
Hadoop is not optimised for ease for use. Installing and integrating with existing databases might prove to be difficult, especially since there is no software support provided. In addition, it is not easy for administration. Because Hadoop requires knowledge of MapReduce, while most data practitioners use SQL. Also Hadoop lacks the level of security functionality needed for safe enterprise deployment, especially if it concerns sensitive data. 
Reference
http://dataconomy.com/hadoop-open-source-software-pros-cons/

CloudTran
CloudTran enables developers to quickly and easily use an IMDG architecture for more than just caching and reading data. Our product provides scalable, ACID-property transactions across data grid nodes as well as transactional persistence to back-end databases and replicated data centers. CloudTran is quick to install and even quicker to use. 
Reference
http://www.cloudtran.com/productOverview.php

Clutrix
Clustrix’s performance grows almost linearly. It shows great scalability, out-of-the-box fault-tolerance, automatically distributing data and increasing the data/memory ratio. So it is great for workloads with high concurrency. However, the performance is not as good under a workload with a small number of threads.
Reference
http://blog.altoros.com/newsql-featured-benchmarks-of-voltdb-nuodb-xeround-tokudb-clustrix-and-memsql.html

CockroachDB
It is a scalable, transactional, geo-replicated data store. CockroachDB aims to address the current lack of an open source, scalable, geo-replicated, ACID compliant database.
Reference
http://test1.infoq.com:8080/news/2014/08/CockroachDB

CodeFuture
Allowing an agile approach to Big Data processing, CodeFutures is transforming static database repositories into a flexible data infrastructure.
CodeFutures Corporation provides database performance tools that reduce the time and effort required to develop database applications and dramatically increase deployed database scalability and performance. It has products: AgilData, MapDB, dbShards etc.
Reference
http://codefutures.com/about/

Continuent
Continuent is a leading provider of database clustering and replication, enabling enterprises to run business-critical applications on cost-effective open source software. 
Continuent Tungsten provides enterprise-class high availability, globally redundant data distribution and real-time heterogeneous data integration in cloud and on-premises environments.
It has benefits like zero-downtime, automatic failover, multi-master, disaster recovery, oracle replication, load balancing, improved performance and supports of mySQL, MariaDB and Percona Sever.
Reference
http://www.continuent.com/solutions

CortexDB
CortexDB is a NoSQL data base technology providing an unlimited platform for individual enterprise web applications at the price of standard software. CortexDB is a schema less
data base with dynamic re-organization during continuous operations. It has benefits such as: flexibility to change the database schema, rapid and agile application development across innovative data services without programming, simple modeling of complex structures.
Reference
http://www.odbms.org/2014/04/cortexdb/

Couchbase
Couchbase Server is a high-performance NoSQL distributed database with a flexible data model. It scales on commodity hardware to support large data sets with a high number of concurrent reads and writes while maintaining low latency and strong consistency. It supports enterprise web, mobile, and IoT applications. It has benefits like elastic scalability, consistent High Performance, availability, flexible, Global Deployment, enterprise-grade administration, real-time big data, developer-focused, data mobility and general purpose.
Reference
http://www.couchbase.com/nosql-databases/couchbase-server

CouchDB
Apache CouchDB? is a database that uses JSON for documents, JavaScript for MapReduce indexes, and regular HTTP for its API. CouchDB is a database that completely embraces the web. CouchDB comes with some benefits, such as on-the-fly document transformation and real-time change notifications, an easy to use web administration console, high availability and partition tolerant, but is also consistent. 
It is best used for accumulating, occasionally changing data, on which pre-defined queries are to be run. Places where versioning is important.
Reference
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis
http://couchdb.apache.org/

databricks/ spark
It provides a single platform for big data processing. Databricks is powered by the 100% open source Apache Spark. Apache Spark is a powerful open source processing engine for Hadoop data built around speed, ease of use, and sophisticated analytics. Spark lets you explore your data in SQL, Python, Java, or Scala, and integrates machine learning, graph computation, streaming analytics, and interactive queries. 
Reference
https://databricks.com/product
https://databricks.com/spark

Datastax
Datastax delivers Apache CassandraTM as part of a database platform purpose built for IOT, Web and Mobile Apps.
Reference
http://www.datastax.com/relational-database-to-nosql

DataTorrent
It provides enterprise-class real-Time stream computation platform for Big Data. DataTorrent supports today’s most demanding, mission-critical, big-data streaming applications. It enables you to quickly develop applications that ingest massive amounts of data from various sources in real-time, and perform highly scalable computations in real-time.
Reference
https://www.datatorrent.com/product/

Datomic
A Datomic database stores a collection of facts. The facts in a database are immutable; once stored, they do not change. However, old facts can be superseded by new facts over time. The state of the database is a value defined by the set of facts in effect at a given moment in time.
Reference
http://docs.datomic.com/architecture.html

DeepDB
It has very high performance with extremely low latency transactions. It maximized disk throughput and accelerated analytics. Besides it minimized storage footprint. DeepDB realizes extremely fast, concurrent data loading and supports continuous backup with snapshots.
Reference
http://deep.is/deepdb-for-mysql/key-features/

EnterpriseDB 
It is the world's leading provider of enterprise-class products and services based on PostgreSQL, the world's most advanced open source database.
Reference
http://www.enterprisedb.com/products-services-training/products-overview

Ehcache
Ehcache is an open source, standards-based cache for boosting performance, offloading your database, and simplifying scalability. It's the most widely-used Java-based cache because it's robust, proven, and full-featured. Ehcache scales from in-process, with one or more nodes, all the way to mixed in-process/out-of-process configurations with terabyte-sized caches.
Reference
http://ehcache.org/

ElasticSearch
It stores JSON documents and enables very versatile and sophisticated querying, scriptable. It also supports geo distance sorting and fuzzy searches, asynchronous replication and atomic, scripted updates. It can maintain automatic "stats groups". It is best used: When you have objects with (flexible) fields, and you need "advanced search" functionality.
Reference
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

Exasol:
Due to intelligent algorithms, EXASolution gets even faster with its usage as conventional DBMS do. At the same time, the amount of administrative work will be strongly reduced, because the on-going tuning is performed by EXASolution itself.
It operates on in-memory data in compressed formats. Besides, exasol write data to what amounts to the in-memory part of their basic data structures; the data then gets persisted to disk. However, exasol is totally optimized for the assumption that queries will be run against data that had already been previously loaded into RAM.
References:
https://www.exasol.com/portal/display/SOL/Database+Administration

FairCom:
It provides high performance SQL AND ISAM database engine which is the foundation for thousands of vertical market, embedded, and corporate applications worldwide. Its products including c-treeRTG, c-treeACE, c-treeAMS.
References:
http://www.faircom.com/ace/products_t.php

FatDB:
It realize tight integration with SQL Server, scale out quickly, development in half the time. It has benefits like consistency, high Availability, partition tolerance, persistence. It is best for rapid application deployment.
However, it only support platforms linux and windows. And it can only be applied to win8 and windows server 2008 operating systems. It cannot be operated on Mobile OS.
References:
http://nosql.findthebest-sw.com/compare/2-23/Cassandra-vs-FatDB

FathomDB
FathomDB makes working with databases easy. It provides relational database-as-a-service, launching MySQL as-a-service on Amazon and Rackspace clouds. It was the first standalone XaaS product for a standard server, a model which has since become ubiquitous. 
FathomDB tackles many of the same technical challenges around running, scaling, and monitoring a realtime database server in the cloud.
References:
http://www.reddit.com/r/Meteor/comments/2ilfkz/meteor_acquires_fathomdb/
http://www.fathomdb.com/

Feedzai
Feedzai, a data science company, offers software that uses big data analysis and machine-based learning to prevent fraud in commerce. Feedzai’s fraud prevention technology fuses big data and machine learning with human intelligence to predict and detect fraud within payment transactions globally. 
References:
https://www.crunchbase.com/organization/feedzai

Firebird
Firebird is a relational database offering many ANSI SQL standard features that runs on Linux, Windows, and a variety of Unix platforms. 
Strengths:
Firebird offers excellent concurrency, high performance, and powerful language support for stored procedures and triggers. Firebird has simpler Windows support, and far less maintenance requirements.
Reference:
http://www.firebirdsql.org/en/about-firebird/

FlockDB
FlockDB is a database that stores graph data, but it isn’t a database optimized for graph-traversal operations. Instead, it’s optimized for very large adjacency lists, fast reads and writes, and page-able set arithmetic queries.
References:
https://blog.twitter.com/2010/introducing-flockdb

FoundationDB
FoundationDB has built a database engine based on the concept of a key-value store, which is a database that is designed to use the data itself as its own index. The key value store supports sharing, hierarchical storage, multi-map storage and quite a number of advanced database concepts. FoundationDB has developed a way to make sure that transactions made using its key value store are ACID compliant. Since these transactions are operating in a distributed environment, they are also very fast.
Weaknesses:
Applications using FoundationDB should plan to work around these limitations. 
The current version of FoundationDB does not support transactions running for over five seconds. 
Transaction size cannot exceed 10 MB of total written keys and values.
There are limitations with key and value sizes. Errors will be raised by the client if these limits are exceeded.
FoundationDB is not a good choice on rotational HDDs when using the ssd engine. 
Key selectors with large offsets are slow.
References:
http://www.zdnet.com/article/foundationdb-a-new-take-on-an-established-data-structure/
https://foundationdb.com/key-value-store/documentation/beta1/known-limitations.html

Galera:
MariaDB Galera Cluster is a synchronous multi-master cluster for MariaDB. It is available on Linux only, and only supports the XtraDB/InnoDB storage engines.
Benefits:
No slave lag, no lost transactions, both read and write scalability, smaller client and latencies.
Limitations:
Galera replication originally only worked with InnoDB storage engine.
DELETE operation is unsupported on tables without primary key. 
Unsupported queries.
Query log cannot be directed to table. 
Maximum allowed transaction size is defined by wsrep_max_ws_rows and wsrep_max_ws_size. Anything bigger (e.g. huge LOAD DATA) will be rejected.
Due to cluster level optimistic concurrency control, transaction issuing COMMIT may still be aborted at that stage. There can be two transactions writing to same rows and committing in separate cluster nodes, and only one of them can successfully commit. The failing one will be aborted. For cluster level aborts, MySQL/galera cluster gives back deadlock error.
XA transactions can not be supported due to possible rollback on commit.
References:
http://support.severalnines.com/entries/21692388-Limitations-in-Galera-Cluster-for-MySQL
https://mariadb.com/kb/en/mariadb/what-is-mariadb-galera-cluster/

GenieDB:
GenieDB provides cloud MySQL Database-as-a-Service (DBaaS) to help easy deployment MySQL database quickly, securely, and at a low cost, so you can instantly get your web applications running on the cloud. GenieDB’s DBaaS uses multi-master replication and multi-regional distribution on multiple cloud infrastructures (Amazon AWS, HP Cloud, Rackspace Cloud, and Google Cloud) to help reduce latency, eliminate downtime, and easily scale your database.
References:
https://www.crunchbase.com/organization/geniedb

GigaSpaces XAP
XAP is an in-memory computing software platform that processes data & apps in real time.
It is an extreme Data Management using in-memory data grid caching. 
It has features as following:
In-memory, partitioned data for scalable & ultra-fast data access.
Ensures immediate consistency, fully supports transactions, rich query semantics & data indexing.
Supports various complex data models (strongly typed, document-based, relational).
References:
http://www.gigaspaces.com/xap-real-time-transaction-processing/overview

Giraph:
Apache Giraph is an iterative graph processing framework, built on top of Apache Hadoop. 
The benefits:
Apache Giraph aims to eliminate this unnecessary overhead by providing a MapReduce compatible solution that is optimized for graph processing applications. Giraph allows the user to write applications that are oriented toward the vertex, with processing performed in memory to eliminate unnecessary job launch and disk interactions. Its Bulk Synchronous Parallel (BSP) based programming model replaces the chain of MapReduce jobs with a single mapper-only job that executes a set of computation actions called “supersteps.”
Limitation:
For fault-tolerance, Giraph uses periodic checkpoints; to coordinate superstep execution,it uses ZooKeeper. Giraph is executed in-memory, which can speedup job execution, but, for large amounts of messages or big datasets, can also lead to crashes due to lack of memory.
References:
Yong Guo, Marcin Biczak, Ana Lucia Varbanescu, Alexandru Iosup, Claudio Martella and Theodore L. Willke. How Well do Graph-Processing Platforms Perform? An Empirical Performance Evaluation and Analysis.
http://giraph.apache.org/intro.html

GridGain:
The GridGain In-Memory Data Fabric is a proven software solution, which delivers unprecedented speed and unlimited scale. It enables high-performance transactions, real-time streaming and fast analytics in a single, comprehensive data access and processing layer. The In-Memory Data Fabric is designed to easily power both existing and new applications in a distributed, massively parallel architecture on affordable, industry-standard hardware.
The advantage of a tree index is that it maintains entries in a sorted order, which is invaluable for many kinds of tasks, where event ordering makes sense. The drawback is that the index entry values should be comparable to each other, and you'll are likely to need to implement a custom comparator for values in place of a default one.
References:
http://www.gridgain.com/products/in-memory-data-fabric/features/

GrapheneDB
GrapheneDB is a cloud hosting platform for the Neo4j graph database.
It create databases instantly and scale easily as your application grows. Our database plans are available on Amazon AWS and Heroku. It extend Neo4j by enabling preconfigured community plugins and extensions like Spatial. Code and roll your own for extra performance and flexibility. It supports Neo4j API.
Reference:
http://docs.graphenedb.com/

Guavus:
Guavus is a big data analytics company developing apps that allow companies to embed data driven-decisions into agile businesses processes. 
The company's Big Data analytics solutions use a highly scalable distributed approach to collect mine and fuse multiple disparate data sources to produce actionable, data and contextually aware insights.
References:
https://www.crunchbase.com/organization/guavus
http://www.guavus.com/products/

Google BigQuery
Querying massive datasets can be time consuming and expensive without the right hardware and infrastructure. Google BigQuery enables super-fast, SQL-like queries against append-only tables, using the processing power of Google's infrastructure to solves this problem. 
Limitation:
BigQuery limits the maximum rate of incoming requests and enforces appropriate quotas on a per-project basis. Specific policies vary depending on resource availability, user profile, service usage history, and other factors, and are subject to change without notice.
Additionally BigQuery has limits on the maximum number of columns per table.
Data format limits: Depending on which format you use to load your data, additional limits may apply.
Reference:
https://cloud.google.com/bigquery/what-is-bigquery
https://cloud.google.com/bigquery/loading-data-into-bigquery#limits

Google App Engine Datastore
App Engine Datastore is a schemaless NoSQL datastore providing robust, scalable storage for your web application, with the following features: no planned downtime, atomic transactions, high availability of reads and writes, strong consistency for reads and ancestor queries and eventual consistency for all other queries.
Weaknesses:
Developers have read-only access to the file system on App Engine.
App Engine can only execute code called from an HTTP request.
Users may upload arbitrary Python modules, but only if they are pure-Python.
Java applications may only use a subset (The JRE Class White List) of the classes from the JRE standard edition.
Java applications cannot create new threads.
Reference:
http://stackoverflow.com/questions/1306279/pros-cons-of-google-app-engine
https://cloud.google.com/appengine/docs/python/datastore/

Google Cloud Datastore
It uses a managed, NoSQL, schemaless database for storing non-relational data. Cloud Datastore automatically scales as you need it and supports transactions as well as robust, SQL-like queries.
It has features as following: Schemaless access, with SQL-like querying. Cloud Datastore is fully managed. Autoscale with users. Cloud Datastore provides ACID transactions using optimistic concurrency control. Built-in redundancy. Local development tools. It enables us to access data from anywhere.
Reference:
https://cloud.google.com/datastore/

Google Compute Engine
It runs large-scale workloads on virtual machines hosted on Google's infrastructure. Choose a VM that fits your needs and gain the performance of Google’s worldwide fiber network.
It has key features as following: high-performance virtual machines, global powered by Google’s global network, global load balancing, fast and easy provisioning, compliance and security.
Reference:
https://cloud.google.com/compute/

Google Cloud SQL
Store and manage data using a fully-managed, relational MySQL database. Google handles replication, patch management and database management to ensure availability and performance. MySQL databases deployed in the cloud without a fuss. Google Cloud Platform provides you with powerful databases that run fast, don’t run out of space and give your application the redundant, reliable storage it needs.
Reference:
https://cloud.google.com/sql/

Hadapt
Hadapt is a cloud-optimized system offering an analytical platform for performing complex analytics on structured and unstructured data. 
Hadapt features include:
All-in-one system for structured, semi-structured, and unstructured data.
Fully integrated platform that eliminates data silos prevalent in "Hadoop connector" based architectures.
Dramatic reduction of ETL workloads and complexities.
Schemaless SQL over non-relational data stores.
The ability to store and analyze JSON, XML, text, and other unstructured data in the same tables as existing structured data.
Identify and present dynamically changing attributes within data.
Adaptive query execution automatically load-balances queries well suited for cloud and virtualized environments.
BI tool integration with Hadapt’s universal SQL support.
Reference:
http://hadapt.com/assets/ESG-Lab-Review-Hadapt-full.pdf
https://www.crunchbase.com/organization/hadapt

Hortonworks Data Platform
It is a completely open source Apache Hadoop data platform, architected for the enterprise.
Its features include: completely open, fundamentally versatile and wholly integrated.
Limitations:
There are some known issues such as HDP 2.1.1 does not support the use of Oracle DB as a metastore. 
References:
http://hortonworks.com/hdp/
http://docs.hortonworks.com/HDPDocuments/HDP2/HDP2.1.7/bk_releasenotes_hdp_2.1/content/ch_relnotes-hdp-2.1.1-knownissues.html

HP Vertica:
HP Vertica provides fast, interactive SQL and advanced analytics for finding business value from your ever-expanding volume and variety of data.
HP Vertica and MapR deliver a comprehensive, scalable, open standards-based solution for big data deployments. Running the HP Vertica Analytics Platform directly on the MapR Big Data Platform provides an optimized, best-of-breed solution for SQL-on-Hadoop to unlock insights from all your data, with a smaller data center footprint than other RDBMS and Hadoop hybrid architectures.
Benefits:
Quickly and cost-effectively ingest, store, and process large volumes of different types, sources, and formats of critical data.
Perform deeper, more advanced analytics directly in Hadoop.
Leverage existing SQL skills, BI tools, and programming expertise.
Implement end-to-end data management and security.
Weakness:
HP Vertica was built for virtualization. Virtualization’s weaknesses are augmented by Vertica’s strengths. 
Reference:
https://www.mapr.com/partners/partner/hp-vertica-delivers-powerful-ansi-sql-analytics-hadoop
http://www.vertica.com/2013/09/25/vertica-in-private-cloud-deployments/

HBase
It has billions of rows X millions of columns and was modeled after Google's BigTable. It uses Hadoop's HDFS as storage. Query predicate push down via server side scan and get filters.
It has optimizations for real time queries and a high performance Thrift gateway. We can random access performance is like MySQL. A cluster consists of several different types of nodes.
It is best used when Hadoop is probably still the best way to run Map/Reduce jobs on huge datasets. Best if you use the Hadoop/HDFS stack already.
Reference:
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

Hypertable 
It is a faster, smaller HBase and implements Google's BigTable design. It runs on Hadoop's HDFS and uses its own, "SQL-like" language, HQL. We can search by key, by cell, or for values in column families. Search can be limited to key/column ranges. Tables are in namespaces. It is best used if you need a better HBase.
Reference:
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

HPCC
HPCC (High Performance Computing Cluster) is a massive parallel-processing computing platform that solves Big Data problems. 
It is open data model. Unlike Hadoop, the data model is defined by the user, and it’s not constrained by the limitations of a strict key-value paradigm.
The solutions to complex data problems can be expressed easily and directly in terms of high level ECL primitives. 
It realize truly parallelism. Nodes of a datagraph can be processed in parallel as data seamlessly flows through them. HPCC effectively results in higher and predictable performance.
The HPCC optimizer ensures that submitted ECL code is executed at the maximum possible speed for the underlying hardware. 
Reference:
http://hpccsystems.com/Why-HPCC/HPCC-vs-Hadoop
http://hpccsystems.com/

HyperGraphDB
HyperGraphDB is a storage framework based on generalized hypergraphs as its underlying data model. It is general purpose, extensible, portable, distributed, embeddable, open-source data storage mechanism. It is a graph database designed specifically for artificial intelligence and semantic web projects, it can also be used as an embedded object-oriented database for projects of all sizes.
Weakness:
It is hard not to understand a typical graph. Also here, HypergraphDB doesn't stick to the general rule. So with graphs this is tricky to model, you would basically need to encode that into probably several dozens if not hundreds of nodes and vertices.
References:
http://highscalability.com/blog/2010/1/26/product-hypergraphdb-a-graph-database.html
http://scalahypergraph.blogspot.com/2012/10/why-hypergraphdb-rocks-and-why-users.html

IMPALA 
Strength:
Scales linearly and vertically, giving you the ability to scale a cluster based on needs.
Impala does not require its own storage engine; it relies on HDFS.
Lives within Hadoop, allowing other computation engines without moving data (i.e. machine learning, batched analysis).
Open source; run it for free.
Limitations:
There are several things that Impala cannot do, which are very important to traditional EDW (Enterprise Data Warehouse). 
Data is immutable, no updating. 
Inserts cannot be done on a single row.
No complex types (maps, arrays, structs) are supported.
The SQL compatibility (the supported SQL statements) is still limited, though new features are being introduced in each new version.
Reference:
Richard L.Saltzer,Istvan Szegedi, Paul De Schacht, Impala in action.  http://www.manning.com/saltzer/ImpalainActionCH01.pdf

IBM Big SQL
Big SQL is designed to provide SQL developers with an easy on-ramp for querying data managed by Hadoop. It enables data administrators to create new tables for data stored in Hive, HBase, or their BigInsights distributed file system. Yet Big SQL doesn't turn Hadoop into one big distributed relational database. 
Big SQL divides execution of a query into parts. Depending on the query, the amount of data, configuration settings, and other factors, Big SQL can execute these parts serially or in parallel. Parallelism is achieved by leveraging Hadoop's MapReduce framework. This can be quite beneficial for complex queries over large data sets.
Limitation:
However, launching a MapReduce job involves a certain amount of processing overhead. This overhead can outweigh the benefits of parallel processing for certain types of queries, such as those that operate over small data sets or retrieve data associated with a specific HBase row key. 
Reference:
http://www.ibm.com/developerworks/library/bd-bigsql/

IBM BigInsights
IBM InfoSphere BigInsights brings the power of Hadoop to the enterprise, accelerating time to value from big data while facilitating rapid big data application development. It enhances Hadoop by adding administrative, discovery, development, provisioning, security, and support, along with best-in-class analytical capabilities. The result is a solution for complex, large scale projects.
Reference:
http://www-01.ibm.com/software/data/infosphere/hadoop/enterprise.html

IBM DB2
DB2 is a family of relational database management system (RDBMS) products from IBM that serve a number of different operating system platforms. According to IBM, DB2 leads in terms of database market share and performance. Although DB2 products are offered for UNIX-based systems and personal computer operating systems, DB2 trails Oracle's database products in UNIX-based systems and  
Microsoft's Access in Windows systems.
It is good and scalable on Z/OS with parallel sysplex, but expensive. Average database in general, strong support, lower cost than Oracle on LUW, less bugs, great optimizer, bad DR, bad HA, and so-so replication, weak SQL-PL stored procedure language, amazing utilities and tracing .
References:
http://www.quora.com/What-are-the-relative-strengths-weaknesses-between-Oracle-database-IBM-DB2-and-Microsoft-SQL
http://searchdatacenter.techtarget.com/definition/DB2

IBM IMS
IBM Information Management System (IMS), built on IBM System z, is the lowest cost transaction and hierarchical database management system for mission critical OLTP. It delivers the highest levels of availability, performance, security, and scalability in the industry. Expansive integration capabilities enable mobile and cloud applications based on IMS assets, enhanced analytics, new application development, SOA exploitation, and more.
IBM IMS Enterprise Suite SOAP Gateway is prone to a security weakness. 
Reference:
http://www-01.ibm.com/software/data/ims/

IBM InfoSphere
The InfoSphere Platform provides all the foundational building blocks of trusted information, including data integration, data warehousing, master data management, big data and information governance.
The platform provides an enterprise-class foundation for information-intensive projects, providing the performance, scalability, reliability and acceleration needed to simplify difficult challenges and deliver trusted information to your business faster.
Limitations:
There are inconsistent experiences with IBM's technical support reported by customers. In addition, uptake of IBM's data federation capabilities beyond DB2-centric environments remains limited. With the growing interest in data federation capabilities for heterogeneous environments, IBM may be at a disadvantage relative to many key competitors (Informatica, Oracle, SAP, SAS, and others) when these capabilities for non-DB2 environments are critical for customers.
Reference:
http://www-01.ibm.com/software/data/infosphere/
http://www.bi-lab.com.ar/ibm-infosphere-datastage-8-1/ibm-infosphere-datastage-8-1/ibm-infosphere-datastage-8-1-gartner

IBM PureData:
The PureData System is optimized exclusively for delivering data services to today's demanding analytic applications. Each of the IBM PureSystems, it offers built-in expertise, integration by design, and a simplified experience throughout its life cycle. It has features as built-in expertise, integration by design and simplified experience.
Reference:
http://www-01.ibm.com/software/data/puredata/

IBM PureData System for Analytics
It is powered by Netezza technology optimizing performance of complex analytics and enables algorithms to run in minutes.
Reference:
http://www.ibm.com/ibm/puresystems/us/en/pf_puredata.html

JethroData 
It is an analytics database combining the scalability of Hadoop HDFS with a fully indexed columnar database. JethroData is an index-based SQL engine for Hadoop. It lets you run 1000 X faster interactive ad-hoc queries, live dashboards and reports. It shares the benefit scalability of Hadoop with the performance of an analytical database, in one system. Queries use indexes to access only the data they need instead of performing a full-scan of the entire dataset, leading to an increase in speed and a dramatic reduction in use of computing resources.
Reference:
https://www.crunchbase.com/organization/jethrodata

jumboDB
It balances performance and cost efficiency. It has benefits as following:
Affordable Big Data with low IO requirements, efficient usage of disk space, low memory footprint.
Fast disk access through compression
Batch processing - delivery driven approach
Supports JSON documents
Power and scalability of Apache Hadoop
Low read latency for end-user apps
Hadoop Connector and Java Driver available
Reference:
http://comsysto.github.io/jumbodb/

JustOneDB:
JustOneDB is a full-featured relational database management system (RDBMS) built on PostgreSQL, but offering unprecedented performance, scalability and agility without the complexity of other Big Data solutions.
JustOneDB delivers a new RDBMS that is completely standards-compliant and ideally suited to the demands of Big Data analytics. JustOneDB possesses all of the advantages of a relational database, and looks exactly like PostgreSQL to applications and business intelligence tools, but with a totally different performance profile.
Limitations and features not currently support:
Analytical queries currently use conventional join strategies and row aggregation and perform similarly to a fully indexed row store.
Not support features: Triggers; Save-points; Unique and key constraints; Text search; Spatial search; Object extensions.
Reference:
https://vardars.wordpress.com/2012/09/03/justonedb/
http://www.justonedb.com/products/justonedb/

InfiniSpan
Infinispan is an open source data grid platform. It is a distributed, in-memory key-value NoSQL store. Infinispan is an extremely scalable, highly available key/value data store and data grid platform. It is 100% open source, and written in Java. The purpose of Infinispan is to expose a data structure that is distributed, highly concurrent and designed ground-up to make the most of modern multi-processor and multi-core architectures. It is often used as a distributed cache, but also as a NoSQL key/value store or object database. Most people use Infinispan for one of two reasons. Firstly, as a distributed cache. Putting Infinispan in front of your database, disk-based NoSQL store or any part of your system that is a bottleneck can greatly help improve performance. Often, a simple cache isn't enough - for example if your application is clustered and cache coherency is important to data consistency. A distributed cache can greatly help here. Infinispan has been used in several industries, ranging from telecoms to financial services, high-end e-commerce to manufacturing systems, gaming and mobile platforms.
References:
http://infinispan.org/about/
http://www.aosabook.org/en/posa/infinispan.html

InfiniSQL:
InfiniSQL is the database for always on, rapid growth applications that need to collect and analyze in real time--even for complex transactions. It has benefits as following:
Reproducible Benchmark. 
Open Source. 
Simplify: Reduce workarounds and point solutions. Standardize on InfiniSQL: no need for sharding, and scales like NoSQL.
Reference:
http://www.infinisql.org/

InfiniteGraph
InfiniteGraph enables organizations to achieve greater return on their data related investment by helping them “connect the dots” on a global scale, ask deeper and more complex questions, across new or existing data stores.
Its key Features include:
Distributed Graph Database; Intuitive, graph-focused Java API optimized for data relationships; Accelerated ingest; Managed placement; Powerful navigation queries; Powerful filtering; Policy-driven consistency models; Indexing and query; Plugin framework; Data Visualization.
Weakness:
It is fine to install as a service, but should make the configuration simple.
Since nodes and edges can be user-customized objects, I suspect the performance will be harmed for huge graphs when we enjoy the flexibility. Remember NoSQL databases should always keep high performance to make themselves compelling. 
Reference:
http://www.objectivity.com/infinitegraph#.VMVcUf7aFIE
http://java.dzone.com/articles/survey-graph-databases-java

InfluxDB
An open-source, distributed, time series database with no external dependencies. InfluxDB is targeted at use cases for DevOps, metrics, sensor data, and real-time analytics. It arose from our need for a database like this on more than a few previous products we’ve built.
Here are some of the features that InfluxDB currently supports:
SQL like query language; HTTP(S) API; Store billions of data points; Database managed retention policies for data; Built in management interface; Pre-aggregate in the database; Store hundreds of thousands of series; Merge multiple series together.
Reference:
http://influxdb.com/docs/v0.8/introduction/overview.html

Informix:
IBM Informix is forging new frontiers with its embeddability and unique ability to seamlessly integrate SQL, NoSQL/JSON, timeseries and spatial data, with a rich set of APIs, including REST, that enhance development simplicity, flexibility and time to market.
Benefits:
Bring NoSQL to SQL database; Options, not hassles, for achieving continuous availability; Increase developer productivity and options; Meet the Big Data challenges of sensor data; Easy administration lets you maximize DBA resources; Speed and efficiency let you do more and spend less; On-the-go connectivity. 
Weakness:
Informix restricts users from creating an additional unique index on a column that has already been indexed "behind the scenes" for a unique constraint.   Informix belongs to script-based class, in which user can include SQL operations or Perl scripts in your HTML Web pages or CGI scripts in order to access a specified database when the Web page is activated. The scripts must ensure that the data is returned i n an HTML-readable form.
Reference:
"An Analysis Of The Strengths And Weaknesses Of The Big Six Database Servers."  123HelpMe.com. 25 Jan 2015 
http://www-01.ibm.com/software/data/informix/

InterSystems Caché
InterSystems Caché is an advanced database management system and rapid application development environment. Caché makes breakthroughs in processing and analyzing complex Big Data, and developing Web and mobile applications. Caché uniquely offers lightning-fast performance, massive scalability, and robust reliability – with minimal maintenance and hardware requirements.
This is a new generation of database technology that provides multiple modes of data access. Data is only described once in a single integrated data dictionary and is instantly available using object access, high-performance SQL, and powerful multidimensional access – all of which can simultaneously access the same data. Caché comes with several built-in scripting languages, and is compatible with the most popular development tools.
Reference:
http://www.intersystems.com/our-products/cache/cache-overview/

Ipedo XML Database
Designed to speed data delivery and transformation in Web and wireless applications, the Ipedo XML Database combines advanced XML query processing with a high-speed native XML database engine. The all-Java server includes advanced XSLT and XPath processing features.
Reference:
http://xml.coverpages.org/ipedoXMLDatabase.html

Iris couch
Iris Couch provides easy hosted CouchDB. Iris Couch is free, cloud CouchDB hosting.
CouchDB can do queries-by-ID without any map-reduce functions, but as soon as you want more complex queries, you need to write a map (and optionally a reduce) function in JavaScript that is stored in the CouchDB server. 
Couch uses an HTTP REST-based interface. Very intuitive, very well designed. 
CouchDB does not store its data as JSON; it stores it as Erlang terms. It actually serializes and deserializes the JSON every time you R/W with the database. CouchDB is safer out of the box.
CouchDB employs a Copy-on-Write/Append-only design almost to a fault.
CouchDB is a distributed multi-master data store.
Large CouchDB deployments pretty much end up using BigCouch. You could also create a fully connected graph of replication rules, depending on problem specifics.
It is best used when you need master-master or you need ultimate single-server durability because you are only going to have a single DB server.
Reference:
http://www.quora.com/How-does-MongoDB-compare-to-CouchDB-What-are-the-advantages-and-disadvantages-of-each
https://www.iriscouch.com/

Kognitio
Kognitio is an in-memory analytical software platform that supports BI, OLAP and analytical applications on large and complex data.
The Kognitio Analytical Platform can be used as a data science lab or to power comprehensive digital marketing analytics; it runs on industry-standard servers, as an appliance, or in Kognitio Cloud, a ready-to-use analytical Platform-as-a-Service (PaaS) in a public or private cloud environment.
Reference:
https://www.crunchbase.com/organization/kognitio

Kx Systems:
Kx offers kdb+, a high-performance column-store database with a built-in expressive query and programming language, q. Used as a central repository to store time-series data within an enterprise, kdb+ supports real-time analysis of billions of records and fast access to terabytes of historical data. It also provides seamless scalability; runs on industry standard server platforms; is top-ranked in third-party benchmark testing; has an extremely small footprint, which makes installation and maintenance fast and straightforward; easily accommodates available APIs for connectivity to major external systems and modules; requires fewer developers, contributing to lower total cost of ownership.
Limitation:
Kx shall not be liable for any damages, and in particular shall not be liable for any special, incidental, consequential, indirect or other similar damages, in connection with or arising out of the use of or inability to use the public q code library files, even if kx has been advised of the possibility of such damages. Such damages include, but are not limited to, loss of profits, revenue or business information.
No support or maintenance.
Reference:
http://kx.com/q/license.txt
http://kx.com/software.php

LevelDB
LevelDB is a light-weight, single-purpose library for persistence with bindings to many platforms.
It has features like: Sorted by keys, arbitrary byte arrays and compressed storage.
Leveldb is essentially a fast key value store implemented as a library that provides key-value store backend for a process. Disadvantage is the key value store can not be accessed by another process in a consistent way. Main advantage is this is a very fast key-value store.
Reference:
http://leveldb.org/
http://www.quora.com/Which-is-the-best-Key-Value-Pair-Database

LogicBlox:
The two key elements of LogicBlox technology are its query language (LogiQL) and its high performance smart database engine. LogiQL empowers users to express sophisticated high-fidelity models in a unified and declarative way, and the smart database optimizes and evaluates the model to find the right answers fast.
LogiQL is designed to be expressive and practical, with only a few simple language constructs. LogiQL is used to build applications that combine transactional, analytical, graph, probabilistic, and mathematical programming. LogiQL makes possible new classes of hybrid applications that are hard or impossible to build on a traditional tech stack that requires a hairball of multiple programming languages and databases.
The LogicBlox database is designed to handle a wide variety of queries and concurrent data access patterns needed for today’s smart applications. It has following features:
Query Optimization, query Evaluation, incremental view maintenance, concurrent transaction management, smarter Predictive Analytics and integrated optimization.
Reference:
http://www.logicblox.com/technology.html

Lokad:
Lokad.Cloud is a framework for distributed computing in Windows Azure, plus a set of independent toolkits like Lokad.Cloud.Storage for simpler and more reliable cloud storage access and Lokad.Cloud.Provisioning for dynamic worker auto-scaling. We use Lokad.Cloud at Lokad to deal with our massive and rapidly changing computation demands.
Benefits:
Non-atomic deployments; Lots of blobs to poll for changes; Replacing an application is easy, getting back not so; Growing demand for stronger runtime
Weakness:
Store everything (assemblies, config, settings) in a single blob and give the currently active blob a special name. Disadvantage: the whole blob can get large and has to be touched by every single settings change. 
Checking a remote repository for changes is more expensive than a simple azure blob storage ETag check (git beats svn here).
Reference: 
http://christoph.ruegg.name/blog/lokadcloud-application-deployment-and-versioning-refresh.html
http://www.lokad.com/forecasting-technology

Lucene:
Apache Lucene is a high-performance, full-featured text search engine library written entirely in Java. It is a technology suitable for nearly any application that requires full-text search, especially cross-platform.
Features:
Scalable, High-Performance Indexing; Powerful, Accurate and Efficient Search Algorithms; Cross-Platform Solution.
Weakness:
The downside of Lucene is that a non-programmer will not be able to figure out how to install, test, configure, and deploy the system. Open source programs are often quite good technically, but some lack the graphical interfaces and training wheels that are standard with some commercial search and content processing systems.
Reference:
http://lucene.apache.org/core/
http://arnoldit.com/wordpress/2008/01/27/lucene-merits-a-test-drive-and-a-close-look/

LucidDB
LucidDB is the first and only open-source RDBMS purpose-built entirely for data warehousing and business intelligence. It is based on architectural cornerstones such as column-store, bitmap indexing, hash join/aggregation, and page-level multiversioning. 
Benefits:
Very high data compression rates for columns with many repeated values; reduced I/O for queries which access only a subset of columns; greater cache effectiveness.
Automatically adapts to either bitmap or btree representation depending on data distribution (even using both in the same index for different portions of the same table), yielding optimal data compression, reduced I/O, and fast evaluation of boolean expressions, without the need for a DBA to choose index type.
Supports read/write concurrency with snapshot consistency, allowing readers to access a table while data is being bulk loaded or updated; versioning at page-level is much more efficient than transactional multi-versioning schemes such as row-level versioning or log-based page reconstruction.
Allows the system to be backed up consistently while queries and ETL are running, eliminating downtime; incremental and compression options minimize archival storage and bandwidth.
Reference:
http://luciddb.sourceforge.net/

MagnetoDB
MagnetoDB is a key-value store service for OpenStack. It provides horizontally scalable, queryable storage, accessible via REST API. MagnetoDB supports Amazon DynamoDB API as well. 
The key features of the MagnetoDB service are:
An easy-to-integrate REST-like API (usable with the AWS SDK, boto clients); 
Schemaless, non-relational table-based model; Put/get/query/scan item operations.
Eventual and strong consistency reads; Local Secondary indexes; Batch read/write operations; Designed to handle any amount of data and any level of request traffic; Seamless throughput and storage scaling; Fault tolerance.
Reference:
https://wiki.openstack.org/wiki/MagnetoDB
https://www.mirantis.com/blog/introducing-magnetodb-nosql-database-service- 
openstack/

MammothDB
MammothDB is an inexpensive enterprise analytics database, provided either in the cloud or on-premises.
MammothDB leverages open source technologies, like Hadoop and MySQL, to deliver an inexpensive massively parallel processing analytics database which complies with industry standards; like STAR data schemas and SQL queries.
Reference:
https://www.crunchbase.com/organization/mammothdb

MapR
MapR is a complete distribution for Apache Hadoop that packages more than a dozen projects from the Hadoop ecosystem to provide you with a broad set of big data capabilities. The MapR platform not only provides enterprise-grade features such as high availability, disaster recovery, security, and full data protection but also allows Hadoop to be easily accessed as traditional network attached storage (NAS) with read-write capabilities.
MapR doesn't provide end-to-end security (strong authentication), which is a big problem for enterprises running shared, multi-tenant clusters. It has a disadvantage of not being as close to the Apache Hadoop mainstream so lack features like security with their initial product offering.
Reference:
http://www.quora.com/How-does-MapR-plan-to-compete-with-Cloudera
https://www.mapr.com/why-hadoop/why-mapr

MariaDB
It is a scalable, highly available and powerful transformative database services with features such as superior scalability, high Availability including zero downtime, developer friendly and powerful transformative services.
Reference:
https://mariadb.com/

MarkLogic
MarkLogic is a software business that makes a NoSQL database, a platform for handling big data applications. MarkLogic's Enterprise NoSQL Database is a new generation database technology capable of handling any data, at any volume, in any structure. 
Benefits:
Powerful and complete platform to speed development. 
Accessible and agile to ensure you see results fast. 
Trusted to run the most mission-critical applications.
Reference:
https://www.crunchbase.com/organization/marklogic
http://www.marklogic.com/

Memcached:
It is open source, high-performance, distributed memory object caching system, generic in nature, but intended for use in speeding up dynamic web applications by alleviating database load.
Memcached is a hosted and distributed key value store and can be extended to use a cluster of nodes each serving consistent copies of the data. Memcached is mainly used as a memory based cache. 
One obvious disadvantage is there is no persistent storage associated with memcached unless entire memory is battery backed up (which is, in most cases, expensive). There are add-on implementations that provide persistent storage backend to memcached like MemcacheDB, CouchBase etc. 
Reference:
http://memcached.org/
http://www.quora.com/Which-is-the-best-Key-Value-Pair-Database

MongoDB 
It is an open-source document database, and the leading NoSQL database. It retains some friendly properties of SQL. (Query, index)
It is best used if you need dynamic queries. If you prefer to define indexes, not map/reduce functions. If you need good performance on a big DB. If you wanted CouchDB, but your data changes too much, filling up disks.
Reference:
http://www.mongodb.org/
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

MemCachier
It implements the memcache protocol but is not based on memcached, the open source daemon.
Reference:
https://www.memcachier.com/how-it-works

Metamarkets
Metamarkets is a real-time analytics platform for the digital advertising space.  We give exchanges, SSPs, DSPs and ad networks the ability to visualize programmatic trends & opportunities as they happen and the freedom to focus on building deeper client relationships instead of software.
Reference:
https://www.crunchbase.com/organization/metamarkets

MetaScale:
MetaScale provides fully scalable, enterprise big data solutions.
MetaScale leverages proven methodologies, best practices, patent pending tools and experienced resources to accelerate the return on big data investment.
MetaScale offers a complete set of Hadoop infrastructure and support services. 
MetaScale can develop and support a robust, open source Hadoop ecosystem that can be scaled to meet your big data needs. We can configure and integrate your Hadoop environment with your structured and unstructured data sources to ensure that you gain value from all of your enterprise data.
Reference:
http://www.metascale.com/

Microsoft HDInsight
HDInsight is based on the Hortonworks Data Platform, which is a completely open source distribution of Apache Hadoo. HDInsight provides a software framework designed to manage, analyze, and report on data. Apache Hadoop core provides reliable data storage with the Hadoop Distributed File System (HDFS), and a simple MapReduce programming model to process and analyze in parallel the data stored in this distributed system. To simplify configuration, management, and running MapReduce jobs, HDinsight provides interactive, web-based consoles which can be used to perform tasks using JavaScript or HiveQL.
Reference:
https://technet.microsoft.com/en-us/library/dn247618.aspx

Microsoft SQL server
The foundation of Microsoft’s comprehensive data platform, SQL Server delivers breakthrough performance for mission-critical applications, using in-memory technologies, faster insights from any data to any user in familiar tools like Excel, and a resilient platform for building, deploying, and managing solutions that span on-premises and cloud.
Benefits:
SQL Server 2014 makes it easier and more cost effective to build high-performance, mission-critical applications, enterprise ready Big Data assets, and BI solutions that help employees make better decisions, faster. These solutions have the flexibility of being deployed on premises, in the cloud or in a hybrid environment, and can be managed through a common and familiar tool set.
Mission-critical performance
SQL Server 2014 accelerates reliable, mission critical applications with a new in-memory OLTP engine that can deliver on average 10x, and up to 30x transactional performance gains. 
Get to insights faster with a complete BI platform that speeds up how you access, analyze, clean and shape both internal and external data. 
Platform for hybrid cloud
Disadvantage:
One of the major disadvantages to using Microsoft SQL Server instead of an alternative relational database management system is that the licensing options are pretty pricey.
Limited Compatibility
Microsoft SQL Server is only designed to run on Windows-based servers. For various reasons, including licensing costs and security concerns, developers may opt to host their websites on Unix-based machines. They would be unable to use SQL Server in this case. Competing products are frequently able to run on other platforms. 
Reference:
http://www.ehow.com/list_6143309_disadvantages-microsoft-sql-server.html
http://www.microsoft.com/en-us/server-cloud/products/sql-server/default.aspx?WT.srch=1&WT.mc_id=SEM_GOO_USEvergreenSearch_Cloud&CR_CC=Unassigned 

Mortar Data
It is a powerful platform for big data processing and analysis.
Mortar seamlessly unites the best technologies for working with data in one simple, solid, scalable platform. Data scientists and engineers use Mortar's instant feedback tools to develop data applications quickly, then run them at scale with a single command. 
Reference:
https://www.crunchbase.com/organization/mortar-data

MySQL
MySQL is the most popular large-scale database servers. It is a feature rich, open-source product that powers a lot of web-sites and applications online. Getting started with MySQL is relatively easy and developers have access to a massive array of information regarding the database on the internet.
Advantages of MySQL: easy to work with, rich feature, security, scalability and powerful and efficiency.
Disadvantages of MySQL: known limitations, less reliability, stagnated development.
Referemce:
https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems

MemSQL
MemSQL is fast with a possibility to use all MySQL client tools. In addition, the troubleshooting becomes much easier due to the use of mySQL. It has weakness including a huge cache folder created by the database in the plancache folder. Besides, MemSQL does not allow you to create users, at least in the developer edition used for the benchmark.
Reference:
http://blog.altoros.com/newsql-featured-benchmarks-of-voltdb-nuodb-xeround-tokudb-clustrix-and-memsql.html

Neo4j
It is a graph database with features as following:
Full ACID conformity (including durable data). Both nodes and relationships can have metadata. Integrated pattern-matching-based query language ("Cypher"). Also the "Gremlin" graph traversal language can be used. Indexing of nodes and relationships. Nice self-contained web admin
Advanced path-finding with multiple algorithms. Indexing of keys and relationships. Optimized for reads. Has transactions (in the Java API).
It is best used for graph-style, rich or complex, interconnected data.
Reference:
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

NGDATA
NGDATA is the consumer intelligence management solutions company that empowers enterprises seeking greater customer lifetime value to drive continuous, actionable insights to enable sales and increase customer loyalty. 
Reference:
https://www.crunchbase.com/organization/ngdata

NuoDB
NuoDB is a scale-out SQL database for the cloud and the modern datacenter. It is the NewSQL solution you need to simplify application deployment.
Different from traditional shared-disk or shared-nothing architectures, NuoDB is a new distributed, peer-to-peer, asynchronous approach. 
Features include:
Durable Distributed Cache; Atoms: Internal Object Structure; Multi-Version Concurrency Control; Data Durability; Commit Protocol; Management and Operations Model
Reference:
http://www.nuodb.com/

Objectivity:
Objectivity/DB, the company’s flagship product and patented object orientated database technology, enables customers to maximize existing infrastructure to capture information needed to address evolving, complex, analytic requirements within Big Data.
Objectivity/DB is an advanced embedded object database technology for developers of critical systems, applications and devices.
Supports virtually any data model, and enables live queries against any data type, volume and source.
Enables Big Data management for high performance, real-time applications in distributed and massively scalable environments.
Ideal for realizing business value from today’s “Internet of Things” by empowering complex Big Data analytics, network analysis, data fusion, and similar systems.
Reference:
http://www.objectivity.com/products/objectivitydb/#.VMWwD_7aFIE

ObjectRocket:
It is a data platform which is scalable, fast, reliable, and automated MongoDB & Redis with Fanatical Support.
Features of it are as follows:
Scalability
As the only inherently sharded MongoDB & Redis service, ObjectRocket enables you to provision an instance in seconds and grow automatically without pain. 
Speed
Optimizing every aspect of the stack specifically for MongoDB & Redis to making MongoDB & Redis as fast as possible.
Safety
When an instance is provisioned, it’s automatically multiplexed across multiple, physically separate systems. Load-balanced mongos servers provide access, and replica sets with at least one secondary are standard. Backups are automatic.Support
There is an easy-to-use, amazing ready-to-go MongoDB & Redis service.
Reference:
https://objectrocket.com/

Openstack trove:
Trove is the database as a service open source project for OpenStack. The mission of Trove is to provide scalable and reliable cloud database as a service provisioning functionality for relational and nonrelational database engines, and to improve its full-featured and extensible open source framework.
There are two primary markets that will benefit from Trove: the first being service providers such as RackSpace who provide cloud-based services similar to Amazon’s AWS. With Trove, much of the management of the database system is taken care of by automating a significant portion of the configuration and initial setup steps necessitated when launching a new server. This includes deployment, configuration, patching, backups, restores, and monitoring that can be administered from either a CLI interface, RESTful API’s or OpenStack’s Horizon dashboard. 
Trove is only able to deliver single instances of SQL/NoSQL databases for customers, but a database in single instance (SI) mode has a set of limitations dictated by the environment where it's installed, primarily related to read/write-operations.
Reference:
https://www.openstack.org/summit/openstack-summit-atlanta-2014/session-videos/presentation/openstack-dbaas-trove-mysql-replication-overview
http://www.percona.com/blog/2014/08/25/openstacks-trove-the-benefits-of-this-database-as-a-service-dbaas/
http://www.tesora.com/openstack/what-is-trove

ObjectStore:
It is the leading in-memory database for applications that demand high-performance, extreme scalability and real time responsiveness. 
ObjectStore stores relationship-centric models that power high performance data processing, analytics, and ACID transactions, leverages in-memory caching and fast event data capture, enables developers to build custom, highly tuned data structures.
Key Differentiating Features:
Achieve high-performance without over-simplifying your data models or compromising transactional integrity
Provide optimal data structure for app performance without compromising durability and availability
Dramatically reduce query latency
Distributed Transactional Caching
Flexible Programming Model
Enable ability to make and handle rapid changes to complex application data models
Reference:
http://www.objectstore.com/product

OrientDB 
It is a document-based graph database with key features as following:
OrientDB as transactions, full ACID conformity. It can be used both as a document and as a graph database. Both nodes and relationships can have metadata. It has Multi-master architecture. It supports relationships between documents via persistent pointers (LINK, LINKSET, LINKMAP, LINKLIST field types). SQL-like query language and web-based GUI (quite good-looking, self-contained). Inheritance between classes. Indexing of nodes and relationships. User functions in SQL or JavaScript.
It is best used for graph-style, rich or complex, interconnected data.
References:
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

Oracle big data appliance:
It delivers comprehensive and secure big data capabilities to the enterprise at a low overall total cost of ownership. It is integrated, optimized, and tuned to shorten deployment times and reduce risk.
It is a high-performance, secure platform for running diverse workloads on Hadoop and NoSQL systems. With Oracle Big Data SQL, Oracle Big Data Appliance extends Oracle’s industry-leading implementation of SQL to Hadoop and NoSQL systems. 
The Oracle Big Data Appliance offers the following benefits:
Rapid provisioning of a highly-available and scalable system for managing massive amounts of data
A high-performance platform for acquiring, organizing, and analyzing big data in Hadoop and using R on raw-data sources 
Control of IT costs by pre-integrating all hardware and software components into a single big data solution that complements enterprise data warehouses
References:
http://www.oracle.com/us/technologies/big-data/big-data-strategy-guide-1536569.pdf
http://www.oracle.com/technetwork/database/bigdata-appliance/overview/index.html
https://www.oracle.com/engineered-systems/big-data-appliance/index.html

Oracle Big Data Cloud
Big Data in the Cloud delivers the power of Hadoop as a secure, managed, elastic, and fully-integrated service. 
Benefits:
Provision fully configured Hadoop clusters on demand. Choose compute shapes and number of nodes based on your needs.
Scale worker nodes based on compute requirements.
Cluster nodes automatically recover upon failure.
Have Oracle manage the cluster for you, or manage it yourself with easy-to-use tooling. Single-click patching and upgrades.
Leverage Oracle Compute Cloud Service’s security lists and rules for flexible enterprise-grade security.
Seamlessly integrate with other Oracle services using big data connectors.
Reference:
https://cloud.oracle.com/bigdata

Oracle Coherence
Oracle Coherence is the industry leading in-memory data grid solution that enables organizations to predictably scale mission-critical applications by providing fast access to frequently used data. As data volumes and customer expectations increase, driven by the “internet of things”, social, mobile, cloud and always-connected devices, so does the need to handle more data in real-time, offload over-burdened shared data services and provide availability guarantees.
Weakness:
The coherence cache implementation is done in Java. There are however also drawbacks in particular when it relates to handling large amounts of data with predictable response time. It is difficult to configure Java garbage collection in order to get good and predictable performance and to avoid time-outs, how many instances one should run each server to avoid to large heap sizes with long GC pauses etc etc.
Another weakness is the support for distributed transactions that is not fully implemented for the cache topology "near cache". This is better supported in some other NOSQL products. 
Another problem is that, in real world use cases, ‘get’ and ‘put’ are not enough. Users inevitably evolve more complex access patterns that necessitate the use of queries and queries don’t scale in the same way.When Coherence executes a query, that query cannot leverage the hashing algorithm used to partition data. Thus the query must be sent to all nodes in the cluster.
In addition, configuring a second backup provides no extra guarantee that the second backup will be held on a different machine to the first, hence loss of two machines may still cause data loss (but the probability of this has been reduced)."
Reference:
http://www.oracle.com/technetwork/middleware/coherence/overview/index.html
https://community.oracle.com/thread/2447944

Oracle Database
An Oracle database is a collection of data treated as a unit. The purpose of a database is to store and retrieve related information. A database server is the key to solving the problems of information management.
Oracle Database is the first database designed for enterprise grid computing, the most flexible and cost effective way to manage information and applications. Enterprise grid computing creates large pools of industry-standard, modular storage and servers. With this architecture, each new system can be rapidly provisioned from the pool of components. There is no need for peak workloads, because capacity can be easily added or reallocated from the resource pools as needed.
Advantages:
Grouping Transactions
The ability to group several transactions into the same batch for processing sets Oracle apart from its competitors. Oracle can expand horizontally by clustering transactions for more efficient processing.
Improved Performance
In addition to batch processing of transactions, Oracle offers other methods of improving your database's performance. 
Versatility
Oracle SQL gives you the flexibility of choosing to run your database in any operating system.
Disadvantages:
Cost
The cost of operating Oracle SQL puts it at a disadvantage in comparison to other versions of SQL. 
Difficulty
Oracle SQL is also more difficult to learn and operate than its competitors. 
References:
http://www.ehow.com/list_6309384_advantages-disadvantages-oracle-sql.html
http://docs.oracle.com/cd/B19306_01/server.102/b14220/intro.htm#i57253

Oracle Exadata
Oracle Exadata is software and hardware engineered together to provide the highest-performing and most-available platform for running Oracle Database. Its architecture features a scale-out design with industry-standard servers and intelligent storage, including state-of-the-art flash technology, and a high-speed InfiniBand internal fabric. Elastic configurations enable systems tailored to specific database workloads.
Advantages:
Infiniband networking between storage and compute nodes, the real source of Exadata's speed.
Hybrid columnar compression.
Index Fast Full Scans.
Absolutely Free Platinum Support Services from Oracle Corporation for Exadata owners.
Disadvantages:
Complex patching due to various layers
You need to open a gateway to the free Oracle Platinum Support for Exadata.
This is not always feasible in production systems carrying sensitive data.
Constant patching is required for any bug fixes.
Reference:
http://www.bayt.com/en/specialties/q/2645/what-are-the-advantages-and-disadvantages-of-oracle-exadata/
https://www.oracle.com/engineered-systems/exadata/index.html

Oracle NoSQL
Oracle NoSQL Database provides a powerful and flexible transaction model that greatly simplifies the process of developing a NoSQL-based application. It scales horizontally with high availability and transparent load balancing even when dynamically adding new capacity.
Data is stored as key-value pairs, which are written to particular storage node(s), based on the hashed value of the primary key. Storage nodes are replicated to ensure high availability, rapid failover in the event of a node failure and optimal load balancing of queries. Customer applications are written using an easy-to-use Java/C API to read and write data.
Oracle NoSQL Driver links with the customer application, providing access to the data via appropriate storage node for the requested key.  A web based console as well as command line interface is available for easy administration of the cluster.
Limitations:
Only support Java programming language.
Don't support mapReduce.
There is also security weakness in NoSQL.
Reference:
http://db-engines.com/en/system/Cassandra%3BOracle+NoSQL

Oracle TimesTen
Oracle TimesTen In-Memory Database is a full-featured relational database that runs in the application tier, storing all data in main memory. This dramatically reduces latency and increases throughput.
For heavy OLTP workload TimesTen can be quite good, considering that NAS storage based traditional database can only reach similar throughput by sacrificing data consistency in BATCH commit mode. If TimesTen is used in grid, the performance can be even better, and data consistency will be also preserved.
Performance of TimesTen really depends on actually cached data and on the size of memory cache. If somehow higher hit rate can be achieved, TimesTen would outperform Oracle Database.
Reference:
http://www.oracle.com/us/products/database/timesten/overview/index.html 
Evaluation of in-memory database TimesTen. http://zenodo.org/record/7566/files/CERN_openlab_report_Endre_Andras_Simon.pdf

Pivotal GemFire
It is the distributed, in-memory database for developers who are building the highest scaling and performing data-centric apps in the world. When you have to process hundreds of thousands of simultaneous transactions involving terabytes of operational data, you need a data management system that can deliver performance at scale, while ensuring consistency of data, and providing high availability and resiliency.
The features of Pivotal GemFire that help customers achieve these capabilities include:
Scale-Out Performance with in-memory storage, performance-optimized disk persistence, configurable consistency and distributed queries.
High Availability, Resilience, and Global Scale.
Easy Administration of Distributed Grids.
Reference:
http://www.pivotal.io/big-data/pivotal-gemfire

Pivotal Greenplum:
Pivotal Greenplum Database (Pivotal GPDB) manages, stores and analyzes terabytes to petabytes of data in large-scale analytic data warehouses around the world. Using the purpose-built Pivotal GPDB platform, your organization can experience 10x, 100x or even 1000x better performance over traditional RDBMS products. Pivotal GPDB extracts the data you need to determine which modern applications will best serve customers in context, at the right location, and during the right activities using a shared-nothing, massively parallel processing (MPP) architecture and flexible column- and row-oriented storage. It also leverages fully parallel communication with external databases and Hadoop to continually harness data.
Reference:
http://www.pivotal.io/big-data/pivotal-greenplum-database

Pivotal SQLfire
It is an in-memory distributed SQL Database that delivers dynamic scalability and high performance for modern, data-intensive applications. The memory-optimized architecture of Pivotal SQLFire minimizes time spent waiting for disk access, the main performance bottleneck in traditional databases. 
Benefits:
Reduced latency for SQL applications — Memory based data management accelerates application performance, eliminating many disk and network latencies.
Standard SQL syntax and tools— Database application developers can easily incorporate a memory-oriented approach to data management with a familiar, standard SQL interface.
Easy scaling to meet the highest demands — Data easily scales out across servers to meet changes in loads or resource availability.
High availability and disaster recovery – Ensures continuous availability within or across datacenters and supports granular disaster recovery to the level of individual tables.
Ideal for high transaction rates — Pivotal SQLFire is ideal for applications such as large transaction oriented Web sites where disk and network overheads choke delivery of many small data items.
Memory-oriented and cloud-optimized – Use of nonproprietary hardware offers an economical way to achieve high database performance at extremely large scale.
Reference:
https://www.pivotal.io/sites/default/files/Pivotal_SQLFire_DS_042213_FINAL.pdf

PostgreSQL:
It is the most advanced, open source SQL-compliant and open-source objective-RDBMS.
Advantages of PostgreSQL
An open-source SQL standard compliant RDBMS:
PostgreSQL is open-source and free, yet a very powerful relational database management system.
It has advantages as following: PostgreSQL is supported by a devoted and experienced community. It has strong third-party support. It is extensible with stored procedures.
It is objective but an objective one - with support for nesting, and more.
Disadvantages of PostgreSQL:
For simple read-heavy operations, PostgreSQL can be an over-kill and might have lower performance. It lacks popularity, despite the very large amount of deployments. It is harder to come by hosts or service providers that offer managed PostgreSQL instances.
Reference:
https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems

Presto
It is an open source distributed SQL query engine for running interactive analytic queries against data sources of all sizes ranging from gigabytes to petabytes. Presto was designed and written from the ground up for interactive analytics and approaches the speed of commercial data warehouses while scaling to the size of organizations like Facebook.
Advantages:
20 times faster than Hadoop/Map-reduce,
Presto efficiently executes complex algorithms such as machine learning, graph processing.
By extending R, Presto allows programmers to leverage optimized math libraries and reuse the many freely available R.
Disadvantages.
It is a licensed software from HP company.
No solution for all type of problems.
Not customized also.
Only R language support.
Spark project is olny query based, not useful for manipulations.
Reference:
http://prestodb.io/
http://www.slideshare.net/sandishk/sparkhadooppresto

The Progress OpenEdge
The Progress OpenEdge Relational Database Management System (RDBMS) leads the database market with low cost of ownership and the ability to scale to meet the demands of enterprise applications, e-commerce and application service providers. 
The OpenEdge database can handle thousands of users and high-traffic loads with sub-second response times. It helps to ensure that users are productive, customers are satisfied, and, for SaaS/Cloud computing environments, service-level agreements are met.
Key benefits include:
Cost effective: Reduce capital and administrative expenses with a database that runs on laptops, desktops and production servers.
Productive: Raise productivity with the highly efficient OpenEdge Advanced Business Language (ABL) and the highly effective OpenEdge SQL as they create and report online transaction processing results.
Easy to administer: OpenEdge production systems' ease of automation and administration allow your database team to focus on service for the business users.
Scalable: OpenEdge applications can scale up to thousands of users and multi-terabyte databases.
Easy to manage: Consolidate datacenter management functions as your business grows.
Reference:
https://www.progress.com/products/openedge/components/rdbms

Qubole
Qubole is a Big Data as a Service (BDaas) Platform Running on Leading Cloud Offerings Like AWS. We Make Fast Data Analysis Super Simple for all Users.
Benefits:
Better Utilization
An auto-scaling cluster, improved I/O optimization, faster queries and support for hybrid pricing — realize significant cost savings (as much as 50%-60% in total) while accomplishing tasks faster.
Instant Deployment
Your Hadoop cluster is ready within minutes post signup, letting you focus on building sophisticated data pipelines, running queries, scheduling jobs and monetizing your big data.
Easy to Use
Provide your data analysts with an easy to use graphical interface, built-in connectors, and seamless, elastic cloud infrastructure—tools that are so intuitive, anyone can use them.
Reference:
http://www.qubole.com/features/

Rackspace:
It provides managed cloud service. Rackspace finds clear business benefits and increasing use of DevOps for rapid software development and deployment.
Disadvantages:
Poor value on the high end - Based on benchmarking we've conducted, performance is about the same between a 1GB and 16GB cloud server - you are basically just paying for more memory. Vertical scaling will be difficult within Rackspace Cloud
Homogenous hardware environment: Cloud servers small or large run on the same AMD hardware and chipset. Contrast this to heterogeneous environments like EC2 which tend to provide better vertical scaling capabilities 
No option for external instance storage: All VMs run off the host system's local storage. If that system were to fail for any reason (i.e. bad motherboard, power supply), your VM will be down until (a) you restore from a backup or (b) Rackspace gets the host system back online
Very limited features in their cloud environment: Rackspace Cloud lacks many of the more advanced cloud features like, auto-scaling, reserve/spot pricing, external storage, reserved IPs, private cloud
Accounts are tied to a single region only: Although Rackspace Cloud is run out of multiple data centers in Texas and Illinois, your account is associated with a single data center only and you can only deploy to that data center
Reference:
http://www.quora.com/What-are-the-disadvantages-of-Rackspace-Cloud-Servers

RavenDB
RavenDB is the open source NoSQL database for .NET. 
Benefits:
It is schema-free and scalable:
Raven supports replication, sharding, and multi-tenancy to work with your big data.
Transactional: In RavenDB, all operations performed on documents are fully transactional.
High Performance: Speed-obsessed. Self-tuning, intelligent indexes, optimized for blazing fast reads, never blocked by locks.
Easy to use: Built in .NET, for .NET. Raven has first-class LINQ support with an idiomatic, clean .NET API served over HTTP.
Extensible: Use bundles like versioning or encryption, or extend RavenDB yourself using well-defined extensibility points.
Lean, powerful, productive: Read more about Raven's awesomeness in the full feature list.
Reference:
http://ravendb.net/

Red Hat JBoss Data Grid
Data grids are in-memory distributed databases designed for scalability and fast access to large volumes of data. More than just a distributed caching solution, data grids also offer additional functionality such as map/reduce, querying, processing for streaming data, and transaction capabilities.
Benefits of JBoss Data Grid:
Performance
Accessing objects from local memory is faster than accessing objects from remote data stores (such as a database). JBoss Data Grid provides an efficient way to store in-memory objects coming from a slower data source, resulting in faster performance than a remote data store. JBoss Data Grid also offers optimization for both clustered and non-clustered caches to further improve performance.
Consistency
JBoss Data Grid uses mechanisms such as cache invalidation and expiration to remove stale data entries from the cache. Additionally, JBoss Data Grid supports JTA, distributed (XA) and two-phase commit transactions along with transaction recovery and a version API to remove or replace data according to saved versions.
Massive Heap and High Availability
In JBoss Data Grid, applications no longer need to delegate the majority of their data lookup processes to a large single server database for performance benefits. 
Scalability
A significant benefit of a distributed data grid over a replicated clustered cache is that a data grid is scalable in terms of both capacity and performance. 
Reference:
http://www.redhat.com/en/technologies/jboss-middleware/data-grid
https://access.redhat.com/documentation/en-US/Red_Hat_JBoss_Data_Grid/6.1/html/Developer_Guide/JBoss_Data_Grid_Benefits2.html

Redis
Redis is an open source, BSD licensed, advanced key-value cache and store. It is often referred to as a data structure server since keys can contain strings, hashes, lists, sets, sorted sets, bitmaps and hyperloglogs. Its key benefit is blazing fast. It is best used for rapidly changing data with a foreseeable database size.
Reference:
http://redis.io/
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

Riak 
Its key benefit is the fault tolerance. Some other features of it tunable trade-offs for distribution and replication. Pre- and post-commit hooks in JavaScript or Erlang, for validation and security. Map/reduce in JavaScript or Erlang. Secondary indices and large object support. Full-text search, indexing, querying with Riak Search.
It is a good fit if you want something Dynamo-like data storage, but no way are you going to deal with the bloat and complexity. If you need very good single-site scalability, availability and fault-tolerance, but you're ready to pay for multi-site replication.
Reference:
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

RethinkDB
RethinkDB is built to store JSON documents, and scale to multiple machines with very little effort. It has a pleasant query language that supports really useful queries like table joins and group by, and is easy to setup and learn.
Benefits:
Simple programming model.
Easy administration.
Horizontal scalability.
RethinkDB compared to other databases.
Reference:
http://rethinkdb.com/

SAP HANA
It is the Platform for Next-Generation applications and analytics. SAP HANA converges database and application platform capabilities in-memory to transform transactions, analytics, text analysis, predictive and spatial processing so businesses can operate in real-time.
The key features of SAP HANA can be summarised as follows:
The in-memory technology lets users explore and analyse all transactional and analytical data in real time from virtually any data source.
Source-agnostic data access & integration services allow accessing and indexing external data from across the entire organisation and adding them to existing analytical models. 
Real-time analytical processing can be performed to analyse business operations in real-time using huge volumes of detailed information while business is happening.
Data can be aggregated from many applications and data sources without perturbing in any way the on-going business transactions.
Views of business information can be persisted in a Persistent Data Repository, and reconstituted in case of a crash.
Real-time Replication Service can be used to access and replicate data from SAP ERP.
Tight integration with SAP Business Objects BI solutions for insight and analytics.
SQL and MDX interfaces for third- party application access.
Unified information modelling and design environment. The great advantage here is that all data models are purely virtual, and calculate results based on the underlying detailed operational data. 
Simplification of existing models, of modelling and re-modelling.
Reduced costs through simplifications in hardware, maintenance and testing.
Simplified Operations and Monitoring with the integration of basic HANA administration capabilities with the BW Admin Cockpit.
Unified information modelling and design environment. The great advantage here is that all data models are purely virtual, and calculate results based on the underlying detailed operational data. 
Simplification of existing models, of modelling and re-modelling.
Reduced costs through simplifications in hardware, maintenance and testing.
Simplified Operations and Monitoring with the integration of basic HANA administration capabilities with the BW Admin Cockpit.
Reference:
http://hana.sap.com/abouthana.html
http://www.infinitesolutions.be/SAP-HANA-Features-and-Benefits

SAP Sybase ASE
SAP Adaptive Server Enterprise (ASE) is a high-performance relational database management system for mission-critical, data-intensive environments. It ensures highest operational efficiency and throughput on a broad range of platforms.
ASE is short for "Adaptive Server Enterprise", the relational database management software manufactured and sold by Sybase, Inc. ASE is a versatile, enterprise-class RDBMS which is especially good at handling OLTP workloads. ASE is used intensively in the financial world (banks, stock exchanges, insurance companies), in E-commerce, as well as in virtually every other area. 
It is best for extreme transaction processing systems that need to support concurrent users with ultra-fast, nonstop performance on cost-effective, standards-based platforms.
Reference:
http://scn.sap.com/community/ase
https://websmp201.sap-ag.de/~sapidp/011000358700001121852012E/index.htm

SAP Sybase IQ
It is best for big data analytics in the real world. With 10 to 100 times faster performance than other traditional database and Hadoop integration, SAP Sybase IQ delivers the performance your customers demand for terabytes and petabytes of data.
Reference:
https://websmp201.sap-ag.de/~sapidp/011000358700001121852012E/index.htm

Sybase SQL Anywhere
It is best for keeping data synchronized with thousands of mobile devices or remote offices, so that all business users can access vital data – anytime, anywhere.
Reference:
https://websmp201.sap-ag.de/~sapidp/011000358700001121852012E/index.htm

ScaleBase:
ScaleBase develops a distributed database management system architected for the cloud. It is a simple, reliable and powerful solution built on MySQL.
ScaleBase enables next generation applications that require big data transactional processing, without changing the existing infrastructure. 
Reference:
https://www.crunchbase.com/organization/scalebase

ScaleDB
It is a software platform, transforms MySQL into a cluster of database servers and storage nodes that manage big data.
ScaleDB provides a MySQL storage engine that makes MySQL work like Oracle RAC, but in the cloud.
ScaleDB adds dynamic elasticity, high-availability, and freedom from the pain of partitioning. ScaleDB turns MySQL into a shared-cache database. Your MySQL application simply scales-out elastically without modification.
Reference:
https://www.crunchbase.com/organization/scaledb

Softlayer
SoftLayer gives you the highest performing cloud infrastructure available. This platform that takes data centers around the world that are full of the widest range of cloud computing options, and then integrates and automates everything.
Three key benefits:
Choice of deployment infrastructure
Unified management for the entire platform
Triple Network Architecture with a dedicated backend network
Reference:
http://www.softlayer.com/our-platform
http://thoughtsoncloud.com/2014/01/three-key-advantages-of-using-softlayer-for-cloud-deployment/

SciDB:
It is the computational DBMS for data-obsessed organizations; programmable from R & Python.
Benefits:
SciDB supports a query language API that allows users to codify the data manipulation they want to do in queries, rather than as procedural code. Query languages are enormously powerful tools. 
SciDB borrows ideas from modern, distributed file-systems. We replicate data chunks on multiple physical nodes to insure against data loss, for example. And because we're obliged to deal with large scale operations, we're working on making our platform continue working even when we lose resources in the middle of a query. 
Weakness:
The transactions does not do very well. We support basic concurrent UPDATE and INSERT operations. We provide isolated transactions. But we're haven't optimized this part of our system's processing. 
It is not pretty immature in the tooling and interaction with other software. Specifically, we don't do things like GIS operations very efficiently. 
Reference:
http://www.scidb.org/
http://www.scidb.org/forum/viewtopic.php?f=6&t=495

Software AG
Software AG helps organizations achieve their business objectives faster. The company’s big data, integration and business process technologies enable customers to drive operational efficiency, modernize their systems and optimize processes for smarter decisions and better service. Building on over 40 years of customer-centric innovation, the company is ranked as a “leader” in more than a dozen market categories, fueled by core product families Adabas-Natural, Alfabet, Apama, ARIS, Terracotta, webMethods and Software AG Live.
Reference:
http://www.softwareag.com/corporate/company/companyinfo/overview/default.asp

SpaceCurve
Introducing SpaceCurve, the spatial data platform that transforms the Internet of Everything into operational intelligence. 
We solved foundational computer science problems to create the first platform purpose-built to spatially organize and analyze machine-generated data sources in real-time at extreme scales. SpaceCurve continuously indexes reality in space and time while making it easily analyzable and immediately actionable.
SpaceCurve delivers a single, seamless, live model of your data. Our core technology ingests and stores data at network speed. You get a real-time, adaptive, spatially organized, distributed index that preserves spatial proximity across all data sources. From ad hoc queries and analytics, to mobile apps and automated actions, SpaceCurve makes it easy to use your data.
Reference:
http://www.spacecurve.com/

Splunk
Splunk offers the leading platform for Operational Intelligence. It enables the curious to look closely at what others ignore—machine data—and find what others never see: insights that can help make your company more productive, profitable, competitive and secure. 
Reference:
http://www.splunk.com/en_us/products.html

SQream
SQream Technologies delivers the World’s most rapid and scalable big data analytics SQL database available on the market. Using a revolutionary technology – SQream enables organizations to easily correlate all their high velocity data, analyze it and figure out the riddles that have been puzzling them thus far. With SQream, the unattainable becomes attainable.
Benefits:
SQream Technologies introduces the first patent-pending innovative technology that boosts analytics performance through massive parallel computing, using a GPU-based technology (Graphic Processing Unit). This revolutionary technology in the Big Data field delivers up to 100 times faster big data analytics than any other key market player, with scalability capabilities surpassing existing database analytics by orders of magnitude – giving organizations a serious technology boost and releasing them from their up-until-now technological limitations that were holding them back trying to attain real-time critical insights.
SQream provides organizations with real-time, comprehensive, actionable insights from enormous data sets through a standard server – saving energy and datacenter floor space, while lowering the TCO.  With SQream, customers of all sizes and needs are able to find the best solution for their unique functional and financial requirements – while powering an entire data center from a box.
Reference:
http://sqream.com/

StarCounter
It is a combined in-memory database engine and application server for ultra fast development of high performance business applications.
StatCounter has a limited “free” option and paid upgrades. The free version has a monthly page view limit (although it is pretty high at 250k), and only limited space for logging. That means they delete some of your data after a period of time. The “detailed logs” are only available for 11 hours before they’re deleted. You can upgrade to get more space for logging and keep track of more page views per month.
Reference:
http://www.nosegraze.com/bbb-question-google-analytics-vs-statcounter/
http://www.starcounter.com/

Stardog:
Stardog is the leading enterprise graph database: search, query, reasoning, and constraints in a lightweight, pure Java system. Stardog is a fast, lightweight, agile semantic graph database—equally adept in client-server, middleware, and embedded modes. 
http://docs.stardog.com/

SQLite
SQLite is a self-contained, file-based database. SQLite offers an amazing set of tools to handle all sorts of data with much less constraint and ease compared to hosted, process based (server) relational databases.
Advantages of SQLite
The entire database consists of a single file on the disk, which makes it extremely portable.
It is great for developing and even testing.
Disadvantages of SQLite: no user management, lack of possibility to tinker with for additional performance.
Reference:
https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems

TempoIQ
TempoIQ is the back-end technology for the world of sensor analytics, offering real-time data monitoring and analysis. 
Benefits:
Flexible Monitoring & Alerts
Build real-time monitoring of sensor data into your application and push alerts to your users based on the conditions that matter to you. TempoIQ enables real-time visibility into your application, so you can understand changing conditions and take action now.
Powerful, Custom Analytics
Add powerful time series and sensor data analytics to your application with rollups, aggregations, interpolation, summaries, annotations and more built in. TempoIQ is optimized for scalable performance, so you can dynamically query your sensor data whether you have one or one million sensors.
Scalable, Secure Backend
Integrate our sensor analytics backend and launch your application now with our simple REST API. TempoIQ supports millions of high sampling rate sensors and long range historical datasets, so you can scale your application with confidence.
Reference:
https://www.tempoiq.com/

TokuDB
TokuDB is able to compress the dataset significantly. In fact, it would be possible to fill TokuDB’s tables with one billion of rows using the same disk size. 
One limitation of it is TokuDB requires sequential primary key inserts.
References:
http://www.percona.com/blog/2013/05/07/benchmarking-percona-server-tokudb-vs-innodb/

TeraData
Teradata delivers an affordable family of purpose built platforms, a high performing technology and innovative industry-specific solutions that enable you to solve a wide range of data warehousing and business challenges. 
They offer the world’s largest and most experienced force of industry, data warehousing and business intelligence consultants who will design and implement your system and enable you to drive top and bottom-line growth.
Reference:
http://www.teradata.com/features-and-benefits/?ICID=Atfb&LangType=1033&LangSelect=true

TIBCO loglogic
TIBCO LogLogic Analytics adds rich visual analytics to the IT data management power and scalability of TIBCO LogLogic, creating a new level of operational and actionable insight to your IT big data.
IT operations teams can collect and analyze terabytes of big data generated by IT assets and find actionable information to identify issues within their environment. Users will gain insight into patterns from potentially thousands of log sources with the ability to filter and explore log data more easily and interactively then ever before.
Thousands of customers already use TIBCO LogLogic to manage their enterprise logging requirements – now with TIBCO LogLogic Analytics they can more effectively unleash the value hiding within their IT data.
Key Features:
Dynamic log data visualization and pattern discovery
Enrich log data with info from disparate data sources for added insight
Integrated predictive analytics and statistical tools
Benefits:
Faster insight into compliance, security or service level issues
Discover relationships and impact you never knew existed
Predict failures, optimize network resources, forecast trends
Reference:
http://www.tibco.com/products/loglogic-analytics-infra

Treasure Data:
Treasure Data is the end-to-end, fully-managed cloud service for Big Data, that’s trusted and simple. It provides flexible cloud service for massive data processing. It brings fast, powerful SQL access to big data from connected applications and products, with no new infrastructure or special skills required.
Benefits:
More data, better decisions.
Grow without efforts.
Leverage SQL skills and BI tools
Integrate seamlessly, export anytime
Reference:
http://www.treasuredata.com/benefits.php
https://www.crunchbase.com/organization/treasure-data

TransLattice
TransLattice is the geographically distributed database company that provides data where and when it is needed, for enterprise, cloud and hybrid environments. This new approach to enterprise and cloud infrastructure results in significantly reduced costs and deployment complexity, while dramatically improving system reliability, scalability and response time. 
Resilience
TransLattice’s self-healing architecture recognizes possible problems and automatically adjusts to prevent disruption in service. 
Elasticity. 
Scaling a TransLattice cluster as simple as deploying additional TransLattice nodes in the new locations and connecting them to your network. As nodes are added, capacity, performance and resilience increase.
Data Governance
Policy-based data location ensures your data complies with applicable regulations and organizational requirements while providing you with a consolidated, global view of all your business operations. 
Lower Cost
TransLattice nodes can be deployed as virtual machines, cloud instances or physical appliances, in any combination, allowing you to expand and contract processing power in sync with the ebb and flow of your business. Economical cloud instances can provide burst capabilities to handle unexpected spikes in workload without investing capital in additional hardware. 
Cloud Migration
Designed to run on many relatively small systems, TransLattice solutions make it easy to move enterprise databases and applications to the cloud.
Performance
TransLattice nodes can be deployed close to end users, wherever they are needed. By placing data on nodes where it is most likely to be used, TransLattice improves response time for end users.
Reference:
http://www.translattice.com/Benefits_Overview.shtml

VoltDB
It has fast transactions and rapidly changing data. Its key features are as follows: In-memory relational database. It is able to export data into Hadoop, supports ANSI SQL, stores procedures in Java and cross-datacenter replication. It is best used: Where you need to act fast on massive amounts of incoming data.
References:
http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

Voldemort
Voldemort is a distributed key-value storage system.
Voldemort offers a number of advantages:
Voldemort combines in memory caching with the storage system so that a separate caching tier is not required (instead the storage system itself is just fast)
Unlike MySQL replication, both reads and writes scale horizontally
Data portioning is transparent, and allows for cluster expansion without rebalancing all data
Data replication and placement is decided by a simple API to be able to accommodate a wide range of application specific strategies
The storage layer is completely mockable so development and unit testing can be done against a throw-away in-memory storage system without needing a real cluster (or even a real storage system) for simple testing.
Reference:
http://www.project-voldemort.com/voldemort/


WakandaDB
It is an Open Source Model-driven NoSQL database engine with a comprehensive REST web interface. The database schema, server-side processing, and querying are all done in JavaScript.
Features:
Wakanda, while its architecture is made to enhance interoperability, wants to propose an already quite complete platform to:
Use an unified language everyone in the development stack can share
Design the Business Objects only once and have them accessible either on the clients and server
Make all the Business Logic, the roles, and Access rights consistent everywhere
Make Debugging and Maintenance more effective
Wakanda can be used as an "Integrated" complete solution to produce a business application.
Wakanda is also capable being interoperable with other systems as server or Database or client.
Challenges:
Platform maturity, interoperability and cloud deployment.
References:
http://forum.wakanda.org/showthread.php?384-Wakanda-server-v.s.-NodeJS-server-strategy!
http://wakandadb.org/
Wakanda white paper, ftp://ftp.wakanda.org/WhitePapers/WhitePaper-IDC-Wakanda.pdf

WebScaleSQL
It is a collaboration among engineers from several companies that face the same challenges in deploying MySQL at scale, and seek greater performance from a database technology tailored for their needs.
Features:
It is an automated framework that will, for each proposed change, run and publish the results of MySQL's built-in test system.
A full new suite of stress tests and a prototype automated performance testing system.
Several changes to improve the performance of WebScaleSQL, including buffer pool flushing improvements, optimizations to certain types of queries, support for NUMA interleave policy, and more.
New features that make operating WebScaleSQL at true web scale easier, such as super_read_only, and the ability to specify sub-second client timeouts.
Limitations:
WebScaleSQL.org said its features improve MySQL scalability while also making it easier to operate at high scale, but that alone won't dent demand for NoSQL databases. Given the companies using WebScaleSQL, there's no doubt that it can scale, but it does so on single, high-powered servers. Though the product is easier to manage at scale than standard MySQL, all these vendors agree on the point that lack of commercial support options will be a deal breaker for most enterprises.
WebScaleSQL is currently only compatible with GNU/Linux x86_64 platforms and no binaries are produced.
https://blog.mariadb.org/mariadb-and-webscalesql/
http://www.informationweek.com/big-data/software-platforms/big-data-vendors-webscalesql-is-no-threat/d/d-id/1141600
http://webscalesql.org/faq.html

Xplenty 
It is a big data cloud platform enabling the transformation of structured and semi-structured data into business insights. 
Benefits:
Xplenty's user-friendly platform is an easy-to-use cloud service that takes the complexity out of Hadoop, so you can quickly transform your structured and semi-structured data into business insights. Xplenty features a set of tools that any data professional can use without special training. It is a complete, cost-effective solution for putting your data into play, from deployment, through import, processing, analysis and monitoring. 
References:
https://www.crunchbase.com/organization/xplenty

YarcData
YarcData delivers business-focused real-time graph analytics for enterprises to gain business insight by discovering unknown relationships in Big Data. 
It provides supercomputing, storage and analytics products are designed to help costomers to tackle the most challenging problems in science, engineering and business.
Reference:
http://www.cray.com/products/analytics/##
https://www.linkedin.com/company/yarcdata

Zettaset 
It is an enterprise software company offering Orchestrator, an enterprise-ready Hadoop cluster management solution for big data. 
Orchestrator significantly improves Hadoop cluster security, availability and performance, and is designed to manage any Apache-based distribution. Unlike other Big Data approaches which are complex and require significant time and resources to implement, Orchestrator is easy to deploy, enabling faster time to value by eliminating unnecessary dependencies on professional services. 
Reference:
https://www.crunchbase.com/organization/goto-metrics

Zimory Scale
Zimory provides carrier-grade cloud infrastructure management software for service providers, enterprises and cloud brokers. 
It has features as following:
It is an open solutiob for all clouds without vendor-lock-in.
It is also complicate for developers to get start. A complete solution for easy to obtain Cloud Services.
It has flexibility scalability. ZIMORY ECO provides greater freedom allowing users take action as needed.
Reference:
http://www.zimory.com/en/technology-and-services/zimory-eco/cloud-orchestration.html
