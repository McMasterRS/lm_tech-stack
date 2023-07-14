---
layout: default
title: Relational Databases
parent: Backend Frameworks
nav_order: 4
---

## Relational Databases

Relational databases are a common type of database that allows users to access data that is stored in different tables connnected by unique IDs and keys. In relational database management systems (RDBMS), users can input SQL queries to retrieve or manipulate data. The main benefit of a relational database is the ability to link data from various tables to create useful information. We will discuss some commonly used open source relational databases below.  

![databases](assets/img/databases.jpg)

_Image retrieved from [pexels.com](https://www.pexels.com/photo/close-up-photo-of-mining-rig-1148820/)_  

### MySQL/MariaDB

MariaDB is an open source distribution of MySQL. MariaDB maintainers provide frequent security releases. While this does not necessarily mean MariaDB is more secure, it does indicate the development community focuses heavily on its software security. MySQL community generated a lot of good documentation over the years, MariaDB inherits these documentation hence it is not difficult for developers to find support during development process.  

MariaDB does not support mobile features natively, so if you are developing application that requires an on-device database you might want to consider alternative relational database management systems. There are some third-party guides and tools to install MariaDB on mobile devices, but it is always better to opt for a database management system that natively support your target platforms.  

### PostgreSQL

PostgreSQL is known to have a great efficiency due to its database engine's central algorithm and it is ideal for software that handle large datasets as database transactions can cause performance bottlenecking by I/O processes. And as one of the most commonly used open source database engines, PostgreSQL has some of the best community support. In addition, PostgreSQL maintainers are actively integrating advanced development tools for [parallelization and clustering](https://wiki.postgresql.org/wiki/Replication,_Clustering,_and_Connection_Pooling).  

#### PostgreSQL or MariaDB?

PostgreSQL and MariaDB are both well-established open source relational database management system. They both have active and vibtant communities, with  a wide range of user support, documentation and resources available. However, since they are different in their database engine's central algorithm, they each have their pros and cons in different use cases in terms of performance, scalability, consistency and availability.  

PostgreSQL emphasizes data integrity and reliability, making it suitable for applications that require strict consistency and complex transactions. It supports multiple transaction isolation levels and provides various mechanisms to ensure data integrity. PostgreSQL can outperform MariaDB in regard to reads and writes though it will come with a larger memory footprint.  

MariaDB, being derived from MySQL, is known for its high reliability and scalability but may have slightly looser consistency guarantees in certain scenarios. MariaDB offers the ability to store less frequently accessed data in a separate partition which can speed up queries. While PostgreSQL does scale well vertically, but it does not scale horizontally as well as MariaDB.  

PostgreSQL is often favored for complex and data-intensive applications, such as enterprise systems, data warehousing, and geospatial applications. Its support for advanced SQL features and extensibility makes it suitable for a wide range of use cases. MariaDB is commonly used for web applications, content management systems, and other scenarios where ease of use and performance are critical.  

Ultimately, the decision between PostgreSQL and MariaDB depends on your specific requirements, familiarity with the databases, and the ecosystem surrounding your project.  

### SQLite

SQLite provide an excellent development alternative for software that are predomaintly read-only or require a smaller package installation footprint. Unlike some client/server SQL database engines mentioned above, those are designed to implement a shared repository of enterprise data. They emphasize scalability, concurrency, centralization and controls and as a result, SQLite is easier to setup than client/server SQL database engines.  
