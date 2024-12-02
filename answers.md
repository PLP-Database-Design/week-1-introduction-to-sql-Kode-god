1. Components of a Database Management System (DBMS)
a)Software: The DBMS software itself, which provides the interface and tools for managing the database. It includes the Database Management System's programs that handle data storage, retrieval, security, and transaction management.
b)Hardware: The physical devices required to run the DBMS, such as servers, storage devices, and networking equipment.
c)Data: The actual data being stored and managed in the database. This includes both the raw data and the metadata that describes the data.
d)Procedure: The set of instructions or policies that govern the operation of the DBMS. This includes backup and recovery procedures, security policies, and the methods for interacting with the database.
e)Data Access Language: This refers to the language used to interact with the database, typically SQL (Structured Query Language). It allows users to query, insert, update, and delete data.
f)Users: The individuals who interact with the DBMS. This includes different types of users such as;Database Administrators (DBAs) and End Users.

2. What is a Relational Database?
A relational database stores data in a structured format, using tables with rows and columns. Relationships between tables are established through primary and foreign keys.
Examples include:
a)MySQL
b)PostgreSQL
c)Microsoft SQL Server

3. Classifications of SQL
SQL can be classified into three major types:
a)Data Definition Language (DDL): Commands to define or modify database structures (e.g., CREATE, ALTER, DROP).
b)Data Manipulation Language (DML): Commands to manage data within the tables (e.g., INSERT, UPDATE, DELETE, SELECT).
c)Data Control Language (DCL): Commands to control access to data (e.g., GRANT, REVOKE).

5. Difference Between a Primary Key and a Foreign Key
Feature	Primary Key	Foreign Key
Primary key	uniquely identifies records in a table while foreign key establishes a relationship with another table.
primary key must be unique for each record while foreign key Can have duplicate values if referencing the same primary key.

6. What is an Entity-Relationship Diagram (ERD)?
An ERD is a visual representation of entities (e.g., people, objects, concepts) and their relationships in a database.

7. Advantages of Relational Databases
Data Integrity: Enforces rules (e.g., primary/foreign keys) to maintain accurate and consistent data.
Flexibility: Data can be easily queried and updated using SQL.
Scalability: Supports large datasets and multiple concurrent users.
Data Security: Provides access controls and permissions to protect data.
Redundancy Minimization: Normalization reduces data duplication.

7. Four Types of Data Types Used in Tables
Integer: Stores whole numbers (e.g., INT, BIGINT).
Character/String: Stores text (e.g., CHAR, VARCHAR, TEXT).
Date/Time: Stores temporal data (e.g., DATE, TIME, TIMESTAMP).
Floating-Point/Decimal: Stores numbers with decimal points (e.g., FLOAT, DECIMAL).

8. Purpose of a Database Management System (DBMS)
The purpose of a DBMS include:
Data Organization: Stores data in a structured format.
Data Retrieval: Allows users to query and retrieve specific data efficiently.
Data Consistency and Integrity: Enforces rules to maintain accurate and consistent data.
Data Security: Protects data with access controls and encryption.
Concurrency Management: Supports multiple users accessing the database simultaneously.
