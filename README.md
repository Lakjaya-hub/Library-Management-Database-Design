#A library service wants to create a database to store details of its libraries, books, and borrowers. Details include the following: A book has a unique ISBN number, a title and one or more authors. The library service may own several copies of a given book, each of which is located in one of the service’s libraries. A given library contains many books, and in order to distinguish different copies of the same book a library assigns a different copy-number to each of its copies of a given book; the price that was paid for each copy is also recorded. Every library has a unique name and is either a main library or a branch library. A main library may have zero or more branch libraries and every branch library is a branch of exactly one main library. A borrower has a name and a unique ID code. A borrower can have many books on loan, but each copy of a book can only be on loan to one borrower. A borrower could borrow the same book on several occasions, but it is assumed that each such loan will take place on a different date. 

The main operation and the details are included here & the developers can suggest some new options and services for the above system. To implement the new and advanced options you can assume any database related structures and constrains.

Tasks

The aim of this coursework is to analyse the above case study to design and develop a database in Microsoft SQL Server including high data integrity and data validation to facilitate the following.

1.	Allow the administrative staff to enter and maintain details about all the project activities. Your application should include appropriate data validation mechanisms (constraints), triggers and user defined functions.
2.	Allow authorized parties to view details to generate meaningful management reports to make strategic, long term and short-term managerial decisions. Your application should include appropriate views and stored procedures to retrieve operational data.

Deliverables

Deliverable 1

You should submit a document containing:

Section 1:
•	A basic introduction to the scenario with the important facts you have identified and considered to your solution. (Do not copy and paste the given scenario as it is)
•	An Entity Relationship (ER) or Extended Entity Relationship (EER) Diagram showing all of the entities, their attributes, relationships, cardinality ratio and the participation constraints. (Should include a sensibly resized diagram which clearly show all the elements)
•	A list of any additional assumptions you have made which affect your solution.
•	Relational Mapping (Have to clearly indicate the steps of relational mapping with all table attributes, primary keys and foreign keys)
•	Data Normalization (Have to clearly indicate all the steps of up data normalization up to Third normalization form).
•	Data Dictionary of each normalized table. (Should contain all the details about each table field)

Section 2:
•	Microsoft SQL Server Create Table statements with related Constraints for each table to validate data. (Should include sensibly resized screenshots of all the table creation statements which clearly show all the SQL statements)
•	Database Diagram of your solution. (Should include a sensibly resized diagram which clearly show all the elements)
•	A set of relevant and sensibly sized screen shots showing all the tables in your application with some meaningful sample records. (Should insert more than 10 meaningful sample records to each table in your database).

Section 3:
•	Microsoft SQL Server Create Trigger statements for the triggers that you have created. (Should create at least two triggers for your database and should provide sensibly resized screenshots of the SQL statements)
•	Microsoft SQL Server Create Function statements for the user defined functions that you have created. (Should create at least two user defined functions for your database and should provide sensibly resized screenshots of the SQL statements)
•	Microsoft SQL Server Create View statements for the database views that you have created. (Should create at least two database views for your database and should provide sensibly resized screenshots of the SQL statements)
•	Microsoft SQL Server Create Procedure statements for the stored procedures that you have created. (Should create at least two stored procedures for your database and should provide sensibly resized screenshots of the SQL statements)



Section 4:
•	A critical appraisal of your solution highlighting worthy features, together with any shortcomings and how they might be resolved.
•	Comments on future implementation of your application. Note that you should include all the SQL queries you have created within your database including Data Definition Language (DDL) and Data Manipulation language (DML) for tables, triggers, views, stored procedures and user defined functions. You should provide sensibly resized screen shots to show all the SQL statements within the database that you have created
