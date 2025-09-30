# database-schema-design-task6-Public
🗂️ SQL Developer Internship : Task 6 – Subqueries & Nested Queries
📌 Objective

The objective of this task is to practice using subqueries in SELECT, WHERE, and FROM clauses.
You will learn how to:

Use scalar subqueries

Write correlated subqueries

Apply subqueries with IN, EXISTS, and =

Build derived tables inside FROM

🛠 Tools Used

DB Browser for SQLite

SQLiteStudio

MySQL Workbench

📂 Deliverables

subqueries_nested.sql file containing:

Scalar & Correlated Subqueries

Subqueries inside IN, EXISTS, =

Derived tables (FROM clause subqueries)

README.md file explaining:

Task overview

Concepts

Outputs

📖 Hints / Mini Guide

Use scalar subqueries for single value comparisons.

Use correlated subqueries when the inner query depends on the outer query.

Use subqueries inside IN, EXISTS, and = for filtering.

Subqueries can also be used in the FROM clause as derived tables.

📖 Interview Questions & Answers

Q1. What is a subquery?
👉 A query inside another SQL query used to fetch data for filtering or calculations.

Q2. Difference between subquery and join?
👉 Subquery executes inner query first, then outer query. Join combines rows from multiple tables in one go.

Q3. What is a correlated subquery?
👉 A subquery that depends on values from the outer query for execution.

Q4. Can subqueries return multiple rows?
👉 Yes, they can. But then they must be used with operators like IN, ANY, or ALL.

Q5. How does EXISTS work?
👉 EXISTS checks whether the subquery returns any rows; returns TRUE if rows exist.

Q6. How is performance affected by subqueries?
👉 Sometimes slower than joins because subqueries may run multiple times (especially correlated ones).

Q7. What is scalar subquery?
👉 A subquery that returns a single value.

Q8. Where can we use subqueries?
👉 In SELECT, WHERE, FROM, and even in HAVING clauses.

Q9. Can a subquery be in FROM clause?
👉 Yes, it becomes a derived table.

Q10. What is a derived table?
👉 A temporary result set from a subquery used as a table in the outer query.

📑 Key Concepts Covered

✅ Subqueries in SELECT, WHERE, and FROM

✅ Scalar & Correlated Subqueries

✅ Filtering with IN, EXISTS, =

✅ Derived Tables

📌 Data Source

Use the library database tables (Book, Member, Loan, Category, Author) created in earlier tasks.
