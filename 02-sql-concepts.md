##  **SQL — Core & Fundamentals**

###  **Basic SQL Concepts**

1. What is SQL? What are its main types of commands (DDL, DML, DCL, TCL)?
2. Difference between SQL, MySQL, and PostgreSQL.
3. What is the difference between a database, schema, and table?
4. What are constraints in SQL? Name different types.
5. What is a primary key vs unique key vs foreign key?
6. What is the difference between `NULL`, `0`, and an empty string?
7. What is normalization? Explain 1NF, 2NF, 3NF, and BCNF with examples.
8. What is denormalization and when would you use it?
9. Difference between `DELETE`, `TRUNCATE`, and `DROP`.
10. What is the difference between `CHAR`, `VARCHAR`, and `TEXT`?

---

##  **SQL — Queries & Clauses**

###  **Select & Filtering**

11. What is the purpose of the `SELECT` statement?
12. Explain the use of `WHERE`, `HAVING`, and `GROUP BY`.
13. Difference between `WHERE` and `HAVING`.
14. What does the `DISTINCT` keyword do?
15. What is the order of execution of SQL clauses (`FROM`, `WHERE`, `GROUP BY`, `HAVING`, `SELECT`, `ORDER BY`)?

---

###  **Aggregation & Functions**

16. What are aggregate functions in SQL?
17. Explain the difference between `COUNT(*)`, `COUNT(column)`, and `COUNT(DISTINCT column)`.
18. What are scalar functions? Give examples.
19. How does `COALESCE()` differ from `ISNULL()`?
20. Write a query to get the second highest salary from an employee table.

---

##  **Joins — Fundamental to Advanced**

###  **Join Basics**

21. What is a JOIN? Why is it used?
22. Explain different types of joins in SQL:

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN
* CROSS JOIN

23. What is a **SELF JOIN**? Give an example.
24. What is the difference between INNER JOIN and OUTER JOIN?
25. Write a query to list all employees and their respective department names (employees without departments should also appear).

---

###  **Join Scenarios**

26. Write a query to find employees who do **not belong** to any department.
27. Write a query to find departments that have **no employees**.
28. Write a query to find employees who have **the same salary** as someone else.
29. How to join more than two tables in SQL? Give an example.
30. What is the difference between `JOIN` and `SUBQUERY` performance-wise?

---

##  **Advanced Queries & Concepts**

###  **Subqueries**

31. What is a subquery?
32. Difference between correlated and non-correlated subquery.
33. Can you use a subquery inside an `INSERT`, `UPDATE`, or `DELETE`?
34. Write a query to find employees whose salary is **greater than the average salary**.
35. Write a query to find employees earning the **top 3 highest salaries**.

---

###  **Window Functions (Analytical Queries)**

36. What are window functions in SQL?
37. Difference between `RANK()`, `DENSE_RANK()`, and `ROW_NUMBER()`.
38. Write a query to display each employee’s salary and their rank in their department.
39. What is the use of `OVER(PARTITION BY ...)` clause?
40. Write a query to calculate a running total of sales for each month.

---

###  **CTE (Common Table Expressions)**

41. What is a CTE? How is it different from a subquery?
42. Write a query using a recursive CTE to display employee hierarchy (manager → employee).
43. Can you use multiple CTEs in a single query?
44. How does CTE improve readability and performance?
45. Write a query using CTE to get department-wise average salary.

---

###  **Set Operators**

46. Difference between `UNION` and `UNION ALL`.
47. What is `INTERSECT` used for?
48. What is the difference between `MINUS` and `EXCEPT`?
49. Write a query to find records that exist in one table but not in another.
50. Explain when you would prefer set operations over joins.

---

##  **Performance & Optimization**

51. What are indexes? Why are they used?
52. Difference between clustered and non-clustered indexes.
53. When should you **not** use an index?
54. What is a composite index?
55. What are the pros and cons of indexes?
56. What is query optimization?
57. How do you identify slow queries in SQL?
58. What is the difference between `EXPLAIN` and `EXECUTION PLAN`?
59. What is the use of indexing on foreign keys?
60. How to avoid full table scans?

---

##  **Data Modification & Transactions**

61. Difference between `INSERT INTO SELECT` and `INSERT VALUES`.
62. How does `UPDATE` differ from `MERGE` statement?
63. What is an atomic transaction?
64. Explain ACID properties.
65. What is the difference between `COMMIT` and `ROLLBACK`?
66. What is a savepoint in SQL?
67. What happens if a transaction fails midway?
68. Can you rollback a single statement in a multi-step transaction?

---

##  **Advanced / Scenario-Based Questions**

69. Write a query to find duplicate records in a table.
70. Write a query to delete duplicate rows but keep one.
71. Write a query to find employees who joined in the **same month** but different years.
72. Write a query to pivot rows into columns.
73. Write a query to unpivot columns into rows.
74. Write a query to fetch the **Nth highest salary** without using `TOP` or `LIMIT`.
75. Write a query to find total sales for each product and percentage contribution to total revenue.
76. Write a query to find gaps in a sequence (e.g., missing invoice numbers).
77. Write a query to find the department having the maximum number of employees.
78. Write a query to show manager names along with the count of employees reporting to them.
79. Write a query to find cumulative sales per region sorted by month.
80. Write a query to transpose data using CASE statements.

---

##  **Database Design & Theory**

81. Difference between OLTP and OLAP systems.
82. What is a surrogate key?
83. Explain referential integrity.
84. What is a view? Difference between a view and a table.
85. Can you update data through a view?
86. Difference between materialized view and regular view.
87. What is a stored procedure? Advantages?
88. What are triggers? When to use them?
89. Difference between function and stored procedure.
90. Explain the difference between `IN`, `EXISTS`, and `JOIN`.

---

##  **Tricky / Real-World Questions**

91. Why is `COUNT(1)` sometimes faster than `COUNT(*)`?
92. How can you find the total number of rows in a huge table efficiently?
93. What’s the difference between `NVL`, `ISNULL`, and `COALESCE`?
94. How to handle duplicate joins or Cartesian products?
95. What is a deadlock? How can you prevent it?
96. Explain isolation levels in SQL (`READ UNCOMMITTED`, `READ COMMITTED`, etc.).
97. What is a surrogate key vs natural key?
98. Explain how indexes can degrade performance during heavy inserts.
99. What are partitioned tables and when to use them?
100. How would you design a table for an e-commerce order system efficiently?

---
