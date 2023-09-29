---
layout: default
title: Non-Relational Databases
parent: Backend Frameworks
nav_order: 6
---

## Non-Relational Databases

A non-relational database, also known as NoSQL (which stands for "not only SQL") database, is a type of DBMS that differs from the traditional relational databases in terms of data organization and storage. NoSQL databases do not use tables, fields and columns structured data concept from relational databases.  

Non-relational databases have been designed with web development in mind, making them great at performaning in web applications and horizontal scaling.  

### MongoDB

MongoDB is a popular open-source NoSQL document database. It is a document-oriented database, meaning it stores data in flexible, JSON-like documents called BSON (Binary JSON) documents.  

BSON documents can contain various types of data, including key-value pairs, arrays, and nested structures. This flexible schema allows for easy storage and retrieval of complex and evolving data. There is no fixed schema that all documents must adhere to. Each document can have its own structure, and fields can be added or modified dynamically without impacting other documents in the collection. This flexibility is particularly useful in scenarios where data structures evolve over time or vary between different documents.  

MongoDB offers features for high availability and fault tolerance. It supports automatic replication, where data is asynchronously replicated to multiple replica sets or nodes to ensure data redundancy and availability. In case of a primary node failure, one of the replicas can be automatically elected as the new primary node.  

MongoDB has a thriving community and a rich ecosystem of tools, libraries, and integrations. It provides official drivers and APIs for various programming languages and has extensive documentation and resources to support developers.  
