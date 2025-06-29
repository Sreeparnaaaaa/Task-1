#Database Setup and Schema Design Solution
##Objective
The objective of this project is to learn how to:

a) Create databases and tables.
b) Define primary and foreign key relationships.
c) Design a well-structured schema and generate an ER diagram.

##Project Overview
This project is based on a Library Management System. It includes the following entities:

a) Author
b) Book
c) Book_Author (Many-to-Many relationship)
d) Member
e) Loan

##Database Schema (Summary)

a) Author table stores author details.
b) Book table stores book details.
c) Book_Author table handles many-to-many relationships between books and authors.
d) Member table stores member details.
e) Loan table tracks the borrowing of books by members.

##ER Diagram
The ER diagram is generated using MySQL Workbench via the Reverse Engineer option.

Relationships:

a) Many-to-Many: Book ⬌ Author
b) One-to-Many: Member ➜ Loan
c) One-to-Many: Book ➜ Loan

