Oracle to SQL Server Migration – HR Schema Practice
🔹 Project Overview

This repository contains a hands-on exercise where Oracle HR schema tables were migrated into SQL Server.
The main goal of this exercise was to understand the syntax differences between Oracle and SQL Server and to practice data migration techniques.

🔹 Objective

Learn the major and minor syntax differences between Oracle and SQL Server.

Practice creating tables, inserting data, and querying across both platforms.

Gain experience in database portability and cross-platform SQL understanding, useful for academic learning and technical interviews.

🔹 Key Steps Performed

Analyzed Oracle HR schema (tables like EMPLOYEES, DEPARTMENTS, JOBS, etc.).

Created equivalent tables in SQL Server with appropriate data types.

Migrated sample records from Oracle to SQL Server.

Explored differences in syntax such as:

NUMBER (Oracle) → INT or DECIMAL (SQL Server)

VARCHAR2 (Oracle) → VARCHAR (SQL Server)

Date functions differences (SYSDATE vs GETDATE())

Constraint definitions (Primary Key, Foreign Key)

Ran queries to validate data consistency between Oracle and SQL Server.

🔹 Key Learnings

Oracle and SQL Server have different default data types and some minor syntax differences.

SQL Server does not support VARCHAR2, uses VARCHAR instead.

Oracle sequences → SQL Server identity columns for auto-increment.

Functions like NVL (Oracle) → ISNULL (SQL Server).

Understanding these differences is crucial for database migration, ETL, and cross-platform projects.

🔹 Technologies Used

Oracle Database – Original HR schema

SQL Server – Target platform for migration

SQL Developer / SSMS – Tools for querying and validation
