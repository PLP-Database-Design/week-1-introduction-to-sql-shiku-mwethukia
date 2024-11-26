### 1. State and Explain the components of a DBMS(Database Management System)

A Database Management System (DBMS) is a software system designed to manage databases efficiently and provide users with tools to store, retrieve, update, and manage data. The key components of a DBMS are as follows:
<li>Hardware - The physical devices used to support the database system, such as servers, storage devices, and networking equipment.
It provides the platform on which the DBMS operates. This includes storage for the database itself and computational power for processing queries and transactions. High-performance hardware ensures the database operates efficiently, especially for large-scale applications.
<li>Software - The DBMS software that manages the database and user applications. This is the core component that provides functionalities such as data storage, retrieval, manipulation, and security. Examples of DBMS software include MySQL, Oracle DB, Microsoft SQL Server, and PostgreSQL. The software acts as an interface between the database, users, and applications.
<li>Data - The raw information stored in the database. Data is the most critical component, as it is the reason for the existence of the DBMS. Data in a DBMS is organized in tables, rows, columns, and records. Proper structuring and indexing of data ensure quick access and efficient management.
<li>Query Processor - The component responsible for interpreting and executing database queries. It translates high-level user queries written in SQL into low-level instructions that the DBMS can understand and execute. The query processor ensures the efficiency and correctness of the queries.
<li>Metadata - Data about the data stored in the database. Metadata includes information about the database schema, such as table structures, relationships, constraints, and data types. It is critical for understanding and managing the database effectively.
<li>Transaction Management - A system to ensure that database transactions are executed reliably. It ensures that all operations within a transaction are completed successfully or none at all (atomicity). It also maintains data consistency and handles concurrent transactions effectively to avoid conflicts.

### 2. What is a relational database? Give 4 examples.
A relational database is a type of database that organizes and stores data in a structured format using tables (also known as relations). Each table consists of rows (records) and columns (fields), where columns define the data attributes (e.g., name, age), and rows represent individual entries or records. 
The defining feature of relational databases is the use of relationships between tables. These relationships are established using keys, such as primary keys (unique identifier for a table) and foreign keys (a reference to a primary key in another table). Relational databases rely on Structured Query Language (SQL) for managing and querying data. Examples include:
<ol type="i">
<li>MySQL: An open-source relational database widely used for web applications, such as WordPress, and commercial software. Known for its speed, reliability, and ease of use.
<li>PostgreSQL: A powerful open-source database known for its advanced features, extensibility, and compliance with ACID (Atomicity, Consistency, Isolation, Durability) principles.
<li>Oracle Database: A commercial relational database system designed for large-scale enterprise applications, known for its robust performance, scalability, and security features.
<li>Microsoft SQL Server: A relational database developed by Microsoft, commonly used in corporate environments for managing and analyzing data.

### 3. State and Explain three classifications of SQL?
<ol type="a">
<li>Data Definition Language (DDL) -  DDL commands are used to define or modify the structure of a database and its objects such as tables, indexes, and schemas. Examples: CREATE, ALTER, DROP, TRUNCATE
<li>Data Manipulation Language (DML) - DML commands are used to manipulate data stored in the database. They help in retrieving, inserting, updating, or deleting data. Examples: SELECT, INSERT, UPDATE, DELETE
<li>Data Control Language (DCL) - DCL commands are used to control access to data in a database. They define permissions and ensure security.
Examples: GRANT, REVOKE

### 4. What is the difference between a Primary Key and a Foreign Key?
A Primary Key is a unique identifier for each record in a table and ensures that each row in a table is unique while a Foreign Key is a field in one table that refers to the primary key in another table and establishes a relationship between two tables.

### 5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a type of visual representation used in database design to illustrate the structure of a database. It depicts how entities (objects or concepts) are related to one another within the system, as well as the attributes and relationships among them. ERDs serve as a blueprint for designing a database and help ensure clarity and accuracy in database design.

### 6. What are the advantages of relational databases?
<li>Data Integrity - Relational databases enforce data integrity through constraints like primary keys, foreign keys, and unique constraints.
<li>Flexibility - Relational databases allow you to easily add, delete, or modify tables, columns, and rows without affecting other parts of the database.
<li>Scalability - They can handle large amounts of data as businesses grow, with tools to optimize performance.
<li>Data Cosistency - Changes made to data are immediately reflected across all relevant tables due to their well-defined relationships.
<li>Security - Relational databases provide robust security features, such as user authentication, role-based access control to limit who can view or modify data and encryption of sensitive information.
<li>Support for ACID Properties - Relational databases adhere to ACID (Atomicity, Consistency, Isolation, Durability) properties.
<li>Data Redundancy Reduction - By normalizing data (breaking it into smaller tables), relational databases eliminate redundancy and save storage space.

### 7. State four types of data type used to store data in tables?
<ol type="i">
<li>Integer
<li>Varchar
<li>Date
<li>Decimal

### 8. What is the purpose of a database management system (DBMS)?  
The primary purpose of a DBMS is to provide a comprehensive and efficient system for managing data, ensuring it is accessible, secure, consistent, and easy to maintain, while supporting complex data operations across multiple users and applications.



