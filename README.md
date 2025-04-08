Library Management System – SQL Project
This project is a Library Management System built entirely using SQL. It aims to simulate a functional and efficient system that manages books, members, book issues, and returns within a library environment.
Project Overview
The SQL script contains the schema design and query logic for managing:
Books and their details


Members of the library


Issued books


Book returns


Penalties for late returns


It demonstrates core SQL concepts like:
Database creation


Table creation with constraints


Relationships via foreign keys


Insert, Update, and delete operations


Join operations


Aggregate functions


Views and stored procedures


Database Structure
Tables Included:
Books – Stores book details like title, author, and genre.


Members – Holds user information.


Issued_Books – Logs books issued to members with issue/return dates.


Returns – Tracks books returned and calculates penalties.


Features:
Relational Integrity: Foreign keys to maintain connections between tables.


Normalization: Optimized structure to avoid redundancy.


Constraints: PRIMARY KEY, UNIQUE, NOT NULL, CHECK constraints applied where needed.



How to Use
Clone the Repository:

 bash
CopyEdit
git clone https://github.com/Love1208-good/project-library-management.git


Open the SQL File:

 Navigate to Library project_sql.txt.


Run the SQL Script:


Open the file in your SQL environment (MySQL Workbench, SQL Server, etc.)


Execute the script step-by-step to create tables and test queries.



SQL Concepts Demonstrated
CREATE, ALTER, DROP


INSERT INTO, UPDATE, DELETE


SELECT with JOIN, GROUP BY, ORDER BY


VIEW and SUBQUERIES


IF, CASE, and Stored Procedures


Use of DATE and DATEDIFF for return penalty calculations



Sample Use Cases
Add a new book to the library.


Register a new library member.


Issue a book to a member.


Return a book and check for fines.


Generate a report of all overdue books.



File Structure
CopyEdit
📁 project-library-management
 └── 📄 Library project_sql.txt


Contributing
Feel free to fork the repository and suggest improvements or additional features via pull requests.



