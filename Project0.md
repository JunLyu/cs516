#CS516 Project0

##Jun Lyu, jl525
#     
##The ordering of the DBs is based on [DB-Engines Ranking](http://db-engines.com/en/ranking)
###Oracle Database

Pros:

* High availability and fully redundant.
* Simple implement, manage and support because of a **complete** system
* Has a great number of supported programming languages

Cons:

* Cost money as a commercial database
	
References:

* Oracle Database Appliance X5­-2, Oracle white paper
* Oracle Database Appliance X5­-2, Oracle Data Sheet
* Oracle System Properties, http://db-engines.com/en/system/Oracle
* Database Buyer's Guide Conclusion: Which Database Is Best for You, http://www.databasejournal.com/features/which-database-is-best-for-you.html

###MySQL
	
Pros:

* An open source database
* High performance and availability
* Scalability through replication
* Wide platform availability and programming language support
	
Cons:

* Has some stability issues
* Not community driven
	
References:

* Top 10 Reasons to Choose MySQL for Next Generation Web Applications, a MySQL white paper
* Five Advantages and Disadvantages of MySQL, https://www.datarealm.com/blog/five-advantages-disadvantages-of-mysql/
* The Pros and Cons of MySQL, http://www.smartfile.com/blog/the-pros-and-cons-of-mysql/

###Microsoft SQL Server
	
Pros:
			
* High availability, scalability and backups
* Use In-Memory OLTP
	
Cons:
			
* High price
* Use its core language
* It has limited compatibility: platforms and languages
	
References:
			
* Introducing Microsoft SQL Server 2014, Technical Overview
* The Disadvantages of a Microsoft SQL Server, http://www.ehow.com/list_6143309_disadvantages-microsoft-sql-server.html
* Advantages & Disadvantages of Microsoft SQL, http://www.ehow.com/list_7228389_advantages-disadvantages-microsoft-sql.html

###PostgreSQL

Pros:

* No licensing cost
* flexibility over relational and non-relational data stores

Cons:

* Somewhat slow due to checked and triggers 

References:

* PostgreSQL 9.4 Increases Flexibility, Scalability and Performance, http://www.postgresql.org/about/news/1557/
* Advantages of PostgreSQL, http://www.postgresql.org/about/advantages/
* Pros and cons about using POSTGRESQL and MYSQL, http://www.postgresql.org/message-id/Pine.LNX.3.96.990827004855.7463B-100000@rabies.toodarkpark.org

###MongoDB

Pros:

* Data can be flexible, no unified data structure, schema-less
* Sharding for large amount of data
* Free MongoDB training
* Improved JavaScript engine

Cons:

* Do not have joins in relational database
* Concurrency control locks entire table
* Do not automatically take operations as transactions
* Few documentations

References:

* The Pros and Cons of MongoDB, http://halls-of-valhalla.org/beta/articles/the-pros-and-cons-of-mongodb,45/
* Pros and cons of MongoDB, http://stackoverflow.com/questions/5244437/pros-and-cons-of-mongodb
* NoSQL showdown: MongoDB vs. Couchbase, http://www.javaworld.com/article/2078750/open-source-tools/nosql-showdown--mongodb-vs--couchbase.html

###IBM DB2

Pros:

* Has powerful SQL features
* Support multiple programming languages
* Use self_tuning memory management

Cons:

* Not as robust as Oracle
* High price

References:

* The Advantages of DB2, http://www.ehow.com/info_12106599_advantages-db2.html
* DB2 System Properties, http://db-engines.com/en/system/DB2
* My SQL, SQL Server, DB2, Oracle Advantages Disadvantages, http://www.experts-exchange.com/Database/Miscellaneous/Q_20562672.html

###Cassandra

Pros:

* Hadoop integration, with MapReduce support
* For distributed and scalable systems

Cons:

* No referential integrity, no joins
* Limited querying options, no ORDER or GROUP

References:

* Cassandra: Pros and Cons, http://marsmedia.info/en/cassandra-pros-cons-and-model.php
* Main disadvantages of using cassandra, http://www.quora.com/What-are-the-main-disadvantages-of-using-cassandra-what-are-the-scenarios-where-cassandra-should-not-be-my-first-selection

###SQLite

Pros:

* Large numbers of supported languages
* Free
* Does not rely on server process

Cons:

* Not all SQL queries are supported
* Sometimes syntax is different
* Concurrency issues
* Require much memory for big database

References:

* A Quick Overview of SQLite, https://h3rald.com/articles/quick-overview-of-sqlite/
* SQLite System Properties, http://db-engines.com/en/system/SQLite

###Redis

Pros:

* Keeps the data loaded in RAM
* Offers data structure such as sets, sorted sets

Cons:

* Only provides key-based search queries
* Not multi-threaded

References:

* Playing around with Redis, pros and cons, https://senecacd.wordpress.com/2013/02/01/playing-around-with-redis-pros-and-cons/
* What are pros and cons of using AWS ElastiCache Redis versus Memcached, http://www.quora.com/What-are-pros-and-cons-of-using-AWS-ElastiCache-Redis-versus-Memcached

###SAP Sybase ASE

Pros:

* High performance, availability, scalability
* Less expensive…

Cons:

References:

* 10 reasons to use Sybase on Linux, http://searchoracle.techtarget.com/tip/Oracle-vs-Sybase-10-reasons-to-use-Sybase-on-Linux

###Lucene/Solr

Pros:

* Has bigger community
* For csv, xml, json etc.
* Has grouping

Cons:

* No routing for indexing and querying

References:

* Why we chose Solr 4.0 instead of ElasticSearch, http://www.ymc.ch/en/why-we-chose-solr-4-0-instead-of-elasticsearch

###Teradata

Pros:

* Options for storing data in both row and column based storage

Cons:

* Depends on primary index

References:

* Vertica vs Aster Data vs Greenplum vs Netezza vs Teradata, http://stackoverflow.com/questions/4528934/vertica-vs-aster-data-vs-greenplum-vs-netezza-vs-teradata

###HBase

Pros:

* Free
* High volume
* Master-Slave Architecture

Cons:

* No security control
* Lacking of aggregate functions
* Concurrency issues
* Single point of failure

References:

* HBase's pros and cons, http://mail-archives.apache.org/mod_mbox/hbase-user/201006.mbox/%3COF26114537.9AC1DB1D-ON4825774A.00108386-4825774A.0010BE0C@tsmc.com%3E
* HBase Architecture Analysis Part 3 Pros and Cons, http://www.cyanny.com/2014/03/13/hbase-architecture-analysis-part-3-pros-cons/

###Elasticsearch

Pros:

* Schemaless
* Has routing for indexing and querying
* Nested docs

Cons:

* Only for json

References:

* Why we chose Solr 4.0 instead of ElasticSearch, http://www.ymc.ch/en/why-we-chose-solr-4-0-instead-of-elasticsearch

###Apache Hive

Pros:

* Use indexing to provide acceleration
* Metadata stored in RDBMS
* Use SQL-like queries
* Operating on compressed data stored into Hadoop ecosystem
* Good for ad hoc queries

Cons:

References:

* Apache Hive, http://en.wikipedia.org/wiki/Apache_Hive
* What are the pros and cons between Pig andHive, http://www.quora.com/What-are-the-pros-and-cons-between-Pig-and-Hive

###Informix

Pros:

* Can power OLTP workloads
* Has NoSQL capability as a relational database
* Can support data warehouse workloads

Cons:

References:

* Key features and enhancements, http://www-01.ibm.com/software/data/informix/features.html

###Memcached

Pros:

* Memory efficient		

Cons:

* Does not offer persistence to disk

References:

* What are pros and cons of using AWS ElastiCache Redis versus Memcached, http://www.quora.com/What-are-pros-and-cons-of-using-AWS-ElastiCache-Redis-versus-Memcached

###Splunk

Pros: 

* Great numbers of apps
* Good search and charting tools

Cons:

* On-premise solution, cost money and complexity

References:

* Pros and Cons of Splunk, http://www.itcentralstation.com/product_reviews/splunk-review-by-tal-weiss


###SAP HANA
Pros:

* Perform analytics on data in transactional system
* Great business efficiency, targeting large enterprise market
* Open for any SAP application
* Not bound to physical hardware
* Slowly merging ecosystem

Cons:

* Is not SaaS
* Does not follow open standards for cloud management
* Hybrid integration is not ready

References:

* Hana Enterprise Cloud - Pro and Cons, http://blogs.forrester.com/stefan_ried/13-05-07-hana_enterprise_cloud_pro_and_cons
* The Suite Life of SAP HANA: Why Customers Will, Won’t Adopt, http://www.asugnews.com/article/the-suite-life-of-sap-hana-why-customers-will-wont-adopt


###CouchDB
Pros:

* Faster on read
* Can easily change schema
* High scalability
* Can easily retrieve and manipulate data with client side languages
* Indexed data make queries faster

Cons:

* Slower write
* Cannot perform complex dynamic queries
* Have to create views for each query
* Generage redundant data

References:

* A week with CouchDB, http://lucdebrouwer.nl/a-week-with-couchdb/
* When to use CouchDB vs RDBMS, http://stackoverflow.com/questions/1307100/when-to-use-couchdb-vs-rdbms


###Neo4j
Pros:

* Can do deep traversals faster than relational database
* Allow fast execution of complex pattern matching queries
* Compact representation of data
* Can represent multiple dimensions
* Transactional

Cons:

* Currently immature
* Lack the capability to optimize queries
* Harder to do summing and max queries
* Need to learn new query language
* Hard to get support

References:

* What are the pros and cons of using a graph database, http://www.quora.com/What-are-the-pros-and-cons-of-using-a-graph-database


###Couchbase
Pros:

* Simple, fast 
* High availability, persistence
* Memcached capabilities
* Support spatial data and views

Cons:

* No transactions
* Index mechanisms not well developed
* Immature JSON support
* Does not support range sharing

References:

* NoSQL Databases, http://nosql.findthebest-sw.com/compare/10-17/HBase-vs-Couchbase-Server
* NoSQL showdown: MongoDB vs. Couchbase, http://www.javaworld.com/article/2078750/open-source-tools/nosql-showdown--mongodb-vs--couchbase.html



###Firebird
Pros:

* Run on many platforms
* Free
* Open source

Cons:

* No integrated replication
* Lower security

References:

* Firebird Pros and Cons, http://www.firebirdsql.org/manual/migration-mssql-pros-cons.html


###Netezza

Pros:

* Use extra set of hardware to handle CPU bottleneck
* Good performance
* Lower price
	
Cons:

* Not good for concurrent querying
* Some hardware issues and system issues 

References:

* Vertica vs Aster Data vs Greenplum vs Netezza vs Teradata, http://stackoverflow.com/questions/4528934/vertica-vs-aster-data-vs-greenplum-vs-netezza-vs-teradata

###MariaDB
Pros:

* More storage engines
* Fast improvements
* Open source

Cons:

* Lots of incompatibilities between MariaDB and MySQL

References:

* MariaDB versus MySQL - Features, https://mariadb.com/kb/en/mariadb/mariadb-vs-mysql-features/
* MariaDB versus MySQL - Compatibility, https://mariadb.com/kb/en/mariadb/mariadb-vs-mysql-compatibility/

###Microsoft Azure SQL Database
Pros:

* A cloud database service
* Featuring strong firewall
* Higher scalability
* No physical administration

Cons:

* Does not cover all SQL features
* No local hosted data
* Charged for outbound data

References:

* Evolution of Windows Azure SQL Database, http://searchsqlserver.techtarget.com/essentialguide/Evolution-of-Windows-Azure-SQL-Database
* The pros of Windows Azure SQL Database, http://searchsqlserver.techtarget.com/feature/The-pros-of-Windows-Azure-SQL-Database
* Why you should think twice about Windows Azure SQL Database, http://searchsqlserver.techtarget.com/feature/Why-you-should-think-twice-about-Windows-Azure-SQL-Database

###Vertica

Pros:

* Lower price
* Data loads in RAM

Cons:

* No GUI tools
* Not good for concurrent querying

References:

* Vertica vs Aster Data vs Greenplum vs Netezza vs Teradata, http://stackoverflow.com/questions/4528934/vertica-vs-aster-data-vs-greenplum-vs-netezza-vs-teradata

###Amazon DynamoDB
Pros:

* High scalability
* Flexible
* Easy administration
* Fault tolerance, monitoring
* Integrate Amazon Elastic MapReduce
* High throughput

Cons:

* Limited row size
* Limited querying
* Only on AWS
* Price
* No ACID
* No atomic transactions
* Hard to check data consistency

References:

* Dynamo DB, http://www.slideshare.net/saniyakhalsa/dynamo-db-pros-and-cons
* What are the pros and cons to DynamoDB's flexible schema, http://www.quora.com/What-are-the-pros-and-cons-to-DynamoDBs-flexible-schema


##After this line, the ordering is alphabetic order


###1010data

Pros:

* Has interactive analytics capability. 
* Can quickly access huge amount of data.
* Fast queries.
* Broad areas of application.

Cons:

* Uses XML-based queries, which limit operation complexity.

References:

* BIG DATA ANALYTICS, https://www.1010data.com/uploads/files/1010data_Robin_Bloor,_Ph_D,_Big_Data_Analytics_white_paper.pdf
* Review: "Did you try big data discovery with 1010data?", http://www.trustradius.com/reviews/1010data-2014-12-12-00-27-32

###Accumulo
Pros:

* High security level: cell level security.
* Use server side programming.
* Scalability and flexibility.
	
Cons:

* Complex data.
	
References:

* Apache Accumulo on Wikipedia, http://en.wikipedia.org/wiki/Apache_Accumulo#cite_note-informationweek1-3
* NoSQL Databases, http://sqrrl.com/product/nosql/
	
###Actian

Pros:

* Analyze large volumes of data.
* Good query performance.

Cons:	
	
References:

* Actian SQL Analytics in Hadoop, http://www.actian.com/wp-content/uploads/2014/12/FINAL-Actian-SQL-Analytics-in-Hadoop-Whitepaper1.pdf

###Adabas

Pros:

* Fast processing ability.
* Multiple platforms.
* High availability.
* Flexible data integration.
	
Cons:

* No embedded SQL engine.
* No referential integrity constraints.
	
References:

* The Adabas Replication Solution, http://www.qualitywriter.com/wp-content/uploads/Samples/White_Papers/Software_AG_Adabas_Replication_White_Paper.pdf
* Adabas on Wikipedia, http://en.wikipedia.org/wiki/ADABAS

###Aerospike

Pros:

* High speed
* Large scale
* Reliable
* Extensible.
	
Cons:

* Less known outside advertising sector
	
Reference:

* Aerospike Architecture Overview, http://pages.aerospike.com/rs/aerospike/images/AerospikeArch_WP_2014.pdf
* Building on success in marketing and ad tech, Aerospike targets broader NoSQL adoption, http://www.aerospike.com/wp-content/uploads/2014/03/Aerospike-Impact-Report-12-Mar-2014.pdf

###AffinityDB

Pros:

* A combination of several database systems.
* Compact query forms.
* SQL for non-relational data
	
Cons:


Reference:

* Affinity Strengths, http://affinityng.cfapps.io/doc/strengths.html

