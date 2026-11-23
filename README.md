# Student Result Management System

## Project Overview

The Student Result Management System is a database management project developed using MySQL. It helps manage student information, classes, subjects, examinations, and academic results.

The project uses SQL operations to store, manage, validate, and analyse student performance. It also generates student report cards and identifies class toppers.

## Technologies Used

- MySQL
- SQL
- MySQL Views
- SQL Triggers
- Transactions (COMMIT and ROLLBACK)

## Database Structure

The project contains five main tables:

| Table Name | Description |
|---|---|
| `classes` | Stores class, section, and class teacher details |
| `students` | Stores student personal and admission details |
| `subjects` | Stores subject names and maximum marks |
| `exams` | Stores examination details and academic years |
| `marks` | Stores student marks and grades |

## Key Features

1. **Student Management:** Stores student details, roll numbers, gender, date of birth, and admission information.

2. **Class Management:** Manages classes, sections, and class teacher information.

3. **Subject Management:** Maintains subject records and maximum marks.

4. **Examination Management:** Stores examination names, dates, and academic years.

5. **Automatic Grade Generation:** Uses SQL triggers to assign grades based on marks obtained.

6. **Marks Validation:** Prevents invalid marks using a validation trigger.

7. **Class Topper Analysis:** Helps identify top-performing students in different classes and sections.

8. **Subject Performance Analysis:** Calculates average, highest, and lowest marks for each subject.

9. **Student Report Card:** Generates total marks, average marks, and percentage using SQL views.

10. **Transaction Management:** Demonstrates COMMIT and ROLLBACK operations to manage database transactions.

## SQL Concepts Implemented

- CREATE DATABASE and CREATE TABLE
- PRIMARY KEY and FOREIGN KEY
- UNIQUE and CHECK Constraints
- INSERT and SELECT Statements
- JOIN Operations
- GROUP BY and ORDER BY
- Aggregate Functions (SUM, AVG, MAX, MIN, COUNT)
- SQL Views
- SQL Triggers
- CROSS JOIN
- CASE Statements
- Transactions (START TRANSACTION, COMMIT, ROLLBACK)
- CSV Data Export

## How to Run the Project

1. Install MySQL Server and MySQL Workbench.
2. Open MySQL Workbench.
3. Open the `student_result_management.sql` file.
4. Execute the SQL script.
5. The database `student_result_management` will be created.
6. Run SELECT queries to view student details, marks, subject analysis, and report cards.

## Sample Reports

The project supports the following reports:

- Student Result Report
- Class Topper Report
- Subject-wise Performance Report
- Total Marks Report
- Average Marks and Percentage Report

## Project Objective

The main objective of this project is to understand relational database management and practical SQL implementation through a real-world student result management scenario.

---

**Project Type:** SQL Database Management System  
**Level:** Beginner to Intermediate  
**Database:** MySQL
