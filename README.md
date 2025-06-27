# SQL Practice

This repository summarizes hands-on SQL practice exercises completed using SQLite and Python (Pandas). 
It focuses on querying real-world business datasets through progressively advanced operations: from simple selection and filtering to multi-join subqueries, all via code-driven analysis.

---

## PART 1: CONNECTING TO SQL DATABASES

* Connected to SQLite databases using `sqlite3` and executed queries via `pandas.read_sql()`.
* Executed SQL commands directly from Python and stored results in DataFrames.
* Worked with sample task schemas to understand foreign key navigation.

---

## PART 2: SELECTING, FILTERING, ORDERING, LIMITING, AND GROUPING DATA

* Queried data using `SELECT`, `WHERE`, `ORDER BY`, and `LIMIT`.
* Used conditional operators (`AND`, `OR`, `NOT`, `IN`, `LIKE`) to filter records.
* Applied aggregate functions (`COUNT`, `SUM`, `AVG`, `MAX`, `MIN`) with `GROUP BY`.
* Implemented `HAVING` clauses to filter group-level results.
* Sorted outputs and limited rows for exploration.

---

## PART 3: SQL TABLE RELATIONS AND JOINS

* Practiced `INNER JOIN`, `LEFT JOIN`, and simulated `FULL OUTER JOIN` logic.
* Mapped one-to-many and many-to-many relationships.
* Performed multi-table joins across `employees`, `offices`, `customers`, `orders`, and `products`.
* Counted distinct entities using `COUNT(DISTINCT ...)`.
* Detected edge cases like empty offices using `LEFT JOIN` with `IS NULL`.

---

## PART 4: SUBQUERIES AND DERIVED TABLES

* Embedded subqueries within `SELECT`, `FROM`, and `WHERE` clauses.
* Created inline views to compute and join custom aggregations.
* Evaluated sales per product using subqueries with filters.
* Compared query outputs with/without `DISTINCT` and studied its effect.
* Identified low-performing products (fewer than 20 unique customers).

---

## PART 5: SQL + PANDAS INTEGRATION & BUSINESS EXERCISES

* Retrieved SQL results into Pandas DataFrames for further analysis.
* Casted fields (e.g., `CAST(amount AS FLOAT)`) to ensure numeric accuracy.
* Solved real-world scenarios:

  * Top employees by average customer credit.
  * Customers with no purchase history.
  * Products by popularity and market reach.
  * Employees tied to underperforming product sales.
  * Detection of offices with zero staff.
* Addressed duplicates and grouped by compound keys like `officeCode, city`.
* Built layered queries and traced logic using nested subqueries.

---

📌 This summary is part of a continuing SQL + Python practice series focused on real analytics use cases.
🛠️ Tools Used: SQLite · Pandas · Jupyter Notebook
📁 Sample Dataset: data.sqlite
➡️ For data analysts, engineers, or bootcamp students enhancing their SQL fluency.
