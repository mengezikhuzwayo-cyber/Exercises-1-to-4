
## Introduction
This repository contains a collection of structured SQL exercises designed to build a strong foundation in database querying and data manipulation. The exercises focus on practical, hands-on learning to help students understand how data is retrieved, filtered, and analyzed within relational databases.

## Aim
The aim of this repository is to develop proficiency in SQL by practicing core concepts used in querying, organizing, and analyzing data effectively.

## Objectives

+ To understand and apply SQL fundamentals
+ To practice writing efficient SELECT statements
+ To learn how to filter data using WHERE clauses
+ To implement sorting techniques using ORDER BY
+ To explore data relationships using different types of JOINS
+ To apply aggregate functions (e.g., COUNT, SUM, AVG)

## Learning Outcomes
+ Write and execute basic to intermediate SQL queries confidently
+ Retrieve and filter data accurately using SQL statements
+ Sort and organize datasets for better readability and analysis
+ Combine data from multiple tables using joins
+ Perform calculations using aggregate functions
+ Apply logical thinking to solve real-world data problems
+ Understand how SQL supports data-driven decision-making


## Sample of Queries 
-- Filter records using WHERE
+ SELECT * 
+ FROM employees
+ WHERE department = 'HR';

-- Sorting statements 
+ SELECT * 
+ FROM employees
+ ORDER BY salary DESC;

-- Using aggregate function
+ SELECT department, AVG(salary) AS avg_salary
+ FROM employees
+ GROUP BY department;



