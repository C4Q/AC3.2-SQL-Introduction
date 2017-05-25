# Introduction to SQL

## Objective

The goal and scope of this to expose the student to SQL through one example environment (AWS) 
and software package (Sequel Pro). The basics of the language are introduced and a simple 
relational problem is worked through.

## Definitions 

### SQL

SQL (Structured Query Language) is a declarative language used to interact with a relational management 
database system (RDBMS). Its statements are divided into two categories, DML and DDL, Data Manipulation
Language and Data Definition Language, respectively. Both DDL and DML statements are sent to the database
in the same way.

### Statement

Each individual unit of SQL is referred to as a statement. It can span more than one line and often does
for readability. 

### Declarative

SQL is a declarative language. This means that its statements are written to describe/declare what the results
should be, without any code defining _how_ the results are accomplished. (Swift, and the majority of languages
by contrast, are imperative languages that allow for the expression of step-by-step algorithmic instructions).

### DDL

DDL, Data Definition Language, is the subset of SQL statements that operate on the structure of the database. 
These operations are done first, chronologically, as DML depends on tables existing before it can be run. It is
possible and common even, to return to the structure of the database and modify it. In more complicated environments
DDL work might be the domain of a DBA (database administrator) and access to it restricted in order to prevent

### DML

DML, Data Manipulation Language, is the subset of SQL statements that read and write data from and to the 
database. Generally, this is where more time is spent by the developer.


### CRUD

CRUD: Create, Read, Update and Delete. Create, here, corresponds not to SQL's DDL statement ```CREATE```, but 
instead to its ```INSERT``` statement

### Client-Server

Most of the time SQL database is accessed using a client-server architecture. The SQL database is a 
central server that a variety of clients connect to and send SQL, listening for responses. One 
notable and familiar exception is the SQLite database that (usually, and by default) backs Core Data. 
This lesson focuses on SQL in a client-server architecture.

## Environment 

### Server - AWS RDS

AWS (Amazon Web Services) is a comprehensive cloud computing product that offers both high level
and low level interfaces to computing resources. Firebase, a Google product, by comparison only
offers a few high level features (authentication, a NoSQL database and storage) using a SaaS model.
AWS has introduced these 

A lot of what is difficult about AWS is security related. AWS uses VPC (Virtual Private Cloud)
to isolate logical networks. It all happens in a network. Your application is usually running on a machine.

The most tangible upshot of this is that you’ll have to make the db accessible from your network.
And yourr network may change

find the security group and change the inbound rules

## Tools

There are myriad SQL front-end tools. Here, we will use Sequel Pro https://www.sequelpro.com/.

Popular SQL implementations

MySQL
PostgreSQL
Oracle
SQL Server
SQLite - slightly weird dialect of SQL

Relational Database (RDBMS)

Normalization
Data Duplication is the devil

Relationships
1:1
1:∞
∞:∞

These three have overlapping meanings
database
schema
user

DDL Data Definition Language
create, drop, alter
create database got;
use got;


DML Data Manipulation Language
select, insert, update, delete

tables
queries
joins


integrity - condider firebase. Consider the final. 
