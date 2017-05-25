# Introduction to SQL

Structured Query Language

## Environment 
AWS RDS

A lot of what is difficult about AWS is security related. AWS uses VPC (Virtual Private Cloud)
to isolate logical networks. It all happens in a network. Your application is usually running on a machine.

The most tangible upshot of this is that you’ll have to make the db accessible from your network.
And yourr network may change

find the security group and change the inbound rules

## Tools
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
