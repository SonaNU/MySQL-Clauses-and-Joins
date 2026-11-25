# MySQL-Clauses-and-Joins

**Project Overview**

This project focuses on practising SQL querying techniques using MySQL. It uses an Employee Database containing employee details, department information, and location records.
The assignment demonstrates how to retrieve, filter, sort, group, aggregate, and combine data from multiple tables using SQL queries.

**Objectives**

- Retrieve unique values using DISTINCT.

- Rename columns using aliases (AS).

- Filter records using WHERE conditions and operators.

- Update missing values in a table.

- Sort records using ORDER BY.

- Restrict query results using LIMIT.

- Perform calculations using aggregate functions.

- Group records using GROUP BY and filter groups using HAVING.
- Combine multiple tables using SQL JOIN operations.

**Database Structure**

Database Name:`employee`

The database contains three tables:

1. Employees

2. Departments

3. Location

SQL Concepts Covered

1. DISTINCT : 
Retrieves unique salary values from the Employees table.

2. Alias (AS) : 
Renames age and salary columns in query results.

3. WHERE Clause and Operators

- Filters employees earning more than ₹50,000 and hired before 1 January 2016.

- Identifies employees with missing designations.

- Updates missing designations to "Data Scientist".

4. ORDER BY : 
Sorts employees by department ID in ascending order and salary in descending order.

5. LIMIT : 
Displays the first five employees hired in 2018.

6. Aggregate Functions

- SUM() – Calculates total salaries in the Finance department.

- MIN() – Finds the minimum employee age.

7. GROUP BY

- Finds the maximum salary for each location.

- Calculates average salary for designations containing the word "Analyst".

8. HAVING

- Finds departments with fewer than three employees.

- Identifies locations with female employees whose average age is below 30.

9. SQL Joins

- INNER JOIN – Retrieves employee names, designations, and department names.

- LEFT JOIN – Displays all departments with employee counts, including departments without employees.

- RIGHT JOIN – Displays all locations with their assigned employee names.\
