SQL Data Querying and Analysis

This project demonstrates various SQL operations and queries for managing a library database. The operations include creating and dropping tables, inserting data, and modifying table schemas. The project is divided into several tasks, each represented by a separate SQL script.

Project Structure

	•	T1-ml-drop.sql: SQL script to drop existing tables.
	•	T1-ml-schm.sql: SQL script to create tables and define their schemas.
	•	T2-ml-insert.sql: SQL script to insert data into the tables.
	•	T2-ml-dm.sql: SQL script for data manipulation, including updates and deletes.
	•	T3-ml-alter.sql: SQL script to alter table structures and perform additional data manipulations.

Getting Started

Prerequisites

	•	SQL database (e.g., Oracle, MySQL, PostgreSQL)
	•	SQL client (e.g., SQL*Plus, MySQL Workbench, pgAdmin)


Detailed Description of Scripts

T1-ml-drop.sql

This script drops all the tables in the database to ensure a clean slate before creating new tables. It uses the DROP TABLE tblname PURGE syntax.

T1-ml-schm.sql

This script creates the necessary tables for the library database, including:

	•	book_copy
	•	loan
	•	reserve
	•	borrower
	•	book_detail
	•	branch
	•	manager

It also defines primary keys, constraints, and column comments for better understanding and data integrity.

T2-ml-insert.sql

This script inserts sample data into the tables created in the previous step. It ensures that the tables are populated with initial data for further operations.

T2-ml-dm.sql

This script performs various data manipulation operations, such as updating and deleting records. It includes:

	•	Updating loan details
	•	Deleting obsolete records
	•	Other necessary data manipulations to maintain database integrity

T3-ml-alter.sql

This script alters the table structures to meet new requirements. It includes:

	•	Adding new columns
	•	Modifying existing columns
	•	Creating new indexes
	•	Updating and inserting data based on new requirements

Author

	•	[Your Name]
	•	Student ID: [Your Student ID]
	•	Tutorial No: [Your Tutorial Number]

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

	•	Thanks to the course instructors for their guidance.
	•	Special thanks to peers and colleagues for their support.

Feel free to adjust the content as needed and add any additional sections or details specific to your project.
