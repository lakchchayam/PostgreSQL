# PostgreSql
Learning Postgre Sql

PostgreSQL is a powerful, open source object-relational database system with over 30 years of active development that 
has earned it a strong reputation for reliability, feature robustness, and performance.

![image](https://user-images.githubusercontent.com/49754403/122557912-063a0880-d05b-11eb-98b9-e72d0497ded2.png)




First, you will learn how to query data from a single table using basic data selection techniques such as selecting columns, sorting result sets, and filtering rows. 
Then, you will learn about the advanced queries such as joining multiple tables, using set operations, and constructing the subquery. 
Finally, you will learn how to manage database tables such as creating new a table or modifying an existing table’s structure.POstgre

What is PostgreSQL? Introduction, History, Features, Advantages
What is PostgreSQL?
PostgreSQL is an enterprise-class open source database management system. It supports both SQL for relational and JSON for non-relational queries. It is backed by an experienced community of developers who have made tremendous contribution to make it highly reliable DBMS system.

PostgreSQL supports advanced data types and advance performance optimization, features only available in the expensive commercial database, like Oracle and SQL Server.

In this tutorial, you will learn

What is PostgreSQL?
A Brief History of PostgreSQL
Key Features of PostgreSQL
MYSQL or POSTGRE SQL
Advantage of PostGRESQL
Disadvantage of PostGRESQL
Applications of PostgreSQL
A Brief History of PostgreSQL
PostgreSQL (initially called Postgres) was created by a computer science professor Michael Stonebraker and his team. Today it has become one of the popular open-source databases.



Let's see some important Milestone from the History of PostgreSQL:

INGRES was developed-1977
Michael Stonebraker and his colleagues developed Postgres- 1986
Support for real ACID and PL/pgSQL - 1990
Released as Postgres95 in -1995
Re-released Postgres95 as PostgreSQL 6.0 - 1996
MVCC, GUC, Join syntax Controls and Procedural Language Loader added- 1998-2001
Version 7.2 to 8.2: Included features like Schema support, Nonblocking VACUUM, Roles and dblink – 2002-2006
PostgreSQL 8.4 released in 2009
PostgreSQL 9.0 released in 2010
NYCPUG (New York City PostgreSQL User Group) joins PgUS (United States PostgreSQL association)- 2013
PGconf organised-2014
Key Features of PostgreSQL
PostgreSQL offers many features that

help developers to build applications
help administrators to build fault-tolerant environment by protecting data integrity.
Here, are some most prominent features of PostgreSQL:

Compatible with various platforms using all major languages and middleware
It offers a most sophisticated locking mechanism
Support for multi-version concurrency control
Mature Server-Side Programming Functionality
Compliant with the ANSI SQL standard
Full support for client-server network architecture
Log-based and trigger-based replication SSL
Standby server and high availability
Object-oriented and ANSI-SQL2008 compatible
Support for JSON allows linking with other data stores like NoSQL which act as a federated hub for polyglot databases.
MYSQL or POSTGRE SQL
MYSQL	POSTGRESQL
The MySQL project has made its source code available under the terms of the GNU License, and other proprietary agreements.	PostgreSQL is released under PostgreSQL License.
It's now owned by Oracle Corporation and offers several paid editions.	It's free and open-source software. That means you will never need to pay anything for this service.
MySQL is ACID compliant only when using with NDB and InnoDB Cluster Storage engines	PostgreSQL is completely ACID compliant.
MySQL performs well in OLAP and OLTP systems where only read speed is important.	PostgreSQL performance works best in systems which demand the execution of complex queries.
MySQL is reliable and works well with BI (Business Intelligence) applications, which are difficult to read	PostgreSQL works well with BI applications. However, it is more suited for Data Warehousing and data analysis applications which need fast read-write speeds.
Advantage of PostGRESQL
PostgreSQL can run dynamic websites and web apps as a LAMP stack option
PostgreSQL's write-ahead logging makes it a highly fault-tolerant database
PostgreSQL source code is freely available under an open source license. This allows you the freedom to use, modify, and implement it as per your business needs.
PostgreSQL supports geographic objects so you can use it for location-based services and geographic information systems
PostgreSQL supports geographic objects so it can be used as a geospatial data store for location-based services and geographic information systems
To learn Postgres, you don't need much training as its easy to use
Low maintenance administration for both embedded and enterprise use
Disadvantage of PostGRESQL
Postgres is not owned by one organization. So, it has had trouble getting its name out there despite being fully featured and comparable to other DBMS systems
Changes made for speed improvement requires more work than MySQL as PostgreSQL focuses on compatibility
Many open source apps support MySQL, but may not support PostgreSQL
On performance metrics, it is slower than MySQL.
Applications of PostgreSQL
Financial Industry

PostgreSQL is an ideal DBMS system for the financial industry. Moreover, It is fully ACID compliant which makes it an ideal choice for OLTP (Online Transaction Processing). It is also capable of performing database analytics. It can be integrated with mathematical software like Matlab and R.

Government GIS data



PostgreSQL offers powerful GIS which is called "PostGIS". This extension provides hundreds of functions to process geometric data in different formats. PostGIS is highly standard compliant. Moreover, by using both QGIS or GeoServer, the Open Source community provides the easiest method to handle Geodata.

Manufacturing

Nowadays, industrial manufacturers also using PostgreSQL to speed up their overall business process. It also helps them to optimize supply chain performance by using this open-source DBMS as storage backend. It allows companies to reduce the operation cost of their business.

Web technology and NoSQL

If your website requires to deal with hundreds or even thousands request per second at that time, scalability is a surely big issue. Here, Postgre proves the best solution.

PostgreSQL works fine with all modern web frameworks like Django, Node.js,

Hibernate, PHP, etc. It also offers replication capabilities which allow to scale out as many database servers as you want.

Scientific data

You need to generate terabytes of data if you are working on research and scientific project. Therefore, it is important to handle in the most efficient way as possible. For that, PostgreSQL offers wonderful analytical capabilities and powerful SQL engine. This helps you to manage a large amount of data with ease.

Summary
PostgreSQL is an enterprise-class open source database management system
PostgreSQL (initially called Postgres) was created by a computer science professor Michael Stonebraker and his team
PostgreSQL is compatible with various platforms using all major languages and middleware
POSTGRES is free and open-source software which means you will never need to pay anything for this service
PostgreSQL can run dynamic websites and web apps as an option to the LAMP stack.
Its supports JSON data.
Postgres is not owned by one organization. So, it has had trouble getting its name out there despite being fully featured and comparable to other DBMS systems
PostgreSQL is widely used in the Financial Industry, Government GIS data, Manufacturing, Web technology, and NoSQL and for Scientific Data collection work
