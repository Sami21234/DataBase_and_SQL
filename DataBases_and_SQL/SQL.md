# SQL(Structured Query Language)

---

SQL (Structured Query Language) is a programming language used for managing 
and manipulating data in relational databases. It allows you to insert, update, 
retrieve, and delete data in a database. It is widely used for data management in 
many applications, websites, and businesses. In simple terms, SQL is used to 
communicate with and control databases.
___

## Types of SQL Commands
1. **DDL(Data Defination Language)** :- 
In this type of SQL command, we create, Modify data 

___

Syntax for creating the database :-
```bash
CREATE DATABASE database_name
```

___

Syntax for deleting the database :-
```bash
DROP DATABASE database_name
```
___
Syntax for creating the table <br>
```bash
CREATE TABLE users(
    col_name data_type,
    col_name data_type,
    col_name data_type,
)
```
---
Syntax for truncating the rows in a table **(make sure while using this command, and first confirm it then use)** <br>
```bash
TRUNCATE TABLE users
```
---
Syntax for Droping the table from the database **(make sure while using this command, and first confirm it then use)** <br>
```bash
DROP TABLE IF EXISTS users
```
