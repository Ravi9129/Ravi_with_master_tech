✅ 10 Basic MSSQL Interview Questions
1️⃣ What is SQL Server? How is it different from MySQL and Oracle?
→ Expect explanation of SQL Server architecture, T-SQL, integration with Windows, licensing, etc.

2️⃣ Explain the difference between a clustered and non-clustered index.
→ Cover how clustered determines physical order, while non-clustered is a separate structure.

3️⃣ What are primary keys and foreign keys? Give syntax to define each.
→ Example: PRIMARY KEY (Id) and FOREIGN KEY (DeptId) REFERENCES Departments(Id).

4️⃣ What is normalization? Name its forms.
→ Up to 3NF/BCNF; e.g., 1NF: atomic values, 2NF: full dependency, 3NF: no transitive dependency.

5️⃣ What is a view? How do you update data using a view?
→ Include INSTEAD OF triggers if needed.

6️⃣ What is a stored procedure? How is it different from a function?
→ Highlight ability to perform modifications vs. scalar/table-valued returns.

7️⃣ How do you use joins? Explain types with examples.
→ INNER, LEFT, RIGHT, FULL OUTER joins.

8️⃣ What is a transaction? Explain ACID properties.
→ Atomicity, Consistency, Isolation, Durability.

9️⃣ How do you back up and restore a database in SQL Server?
→ Commands: BACKUP DATABASE ... TO DISK=... & RESTORE DATABASE.

🔟 How do you find duplicate records in a table?
→ Using GROUP BY + HAVING COUNT(*) > 1.

✅ 80 Advanced & Scenario-Based MSSQL Interview Questions
🔹 Indexing & Performance Tuning
How do you identify missing indexes in a production environment?

Explain how index fragmentation impacts performance. How do you fix it?

What is the difference between REBUILD and REORGANIZE for indexes?

How do included columns in indexes help performance?

When would you use a filtered index? Give a real use case.

What is the query execution plan, and how do you read it?

How would you optimize a slow-running query used in a high-traffic web app?

Explain parameter sniffing and its impact on performance.

What is a covering index? Provide an example.

How do you capture long-running queries? Tools & scripts?

🔹 Query Optimization & Design
How do you rewrite a cursor-based query into a set-based solution?

When would you use a common table expression (CTE) vs. a temp table?

How do table variables compare with temp tables in performance?

What are indexed views? What are the requirements to create them?

How do you handle performance issues with OR conditions in WHERE clause?

Explain SARGability. How does it affect query performance?

Give an example of a deadlock scenario and how to resolve it.

What is OPTIMIZE FOR UNKNOWN?

How do you analyze and interpret execution plan operators like SEEK, SCAN, HASH MATCH?

What strategies do you use to minimize blocking?

🔹 Concurrency & Transactions
Describe transaction isolation levels. When would you choose READ COMMITTED SNAPSHOT?

How do you avoid deadlocks in a multi-user environment?

How does NOLOCK hint work? When should you avoid it?

Explain optimistic vs. pessimistic concurrency control with examples.

How do you identify the root cause of a deadlock from logs?

How would you design a transaction-safe bulk insert process?

What is a savepoint in transactions? How would you use it?

🔹 Data Modeling & Architecture
How do you decide between normalization and denormalization?

How would you design a schema for a multi-tenant SaaS product?

How do you partition large tables? When is partitioning needed?

What are filegroups? Why would you use them?

Explain sharding and its pros/cons for scaling databases.

How do you manage schema changes on large production databases?

🔹 Security
How do you implement row-level security in SQL Server?

What are server and database roles? Give examples.

How do you securely store and retrieve encrypted data?

Explain SQL injection and how to prevent it in T-SQL code.

How do you audit data access in a sensitive table?

🔹 High Availability & Recovery
What is database mirroring? Differences with AlwaysOn Availability Groups?

How does log shipping work? Where would you use it?

What is replication? Types of replication supported in SQL Server.

How do you implement point-in-time recovery?

What strategies do you use for disaster recovery planning?

🔹 Advanced Development
What are CROSS APPLY and OUTER APPLY? Provide real examples.

Explain recursive CTEs with example usage.

What is FOR XML PATH? How do you use it for string aggregation?

How do you handle hierarchical data (e.g., organizational charts)?

What is the MERGE statement? Give a practical scenario.

🔹 Real-World Scenarios & Problems
A report suddenly starts timing out after a new deployment. How would you troubleshoot?

How do you detect and clean orphaned users in a database?

You need to migrate 1TB of data with minimal downtime. What approach would you use?

How do you enforce soft deletes in tables without impacting performance?

How do you archive historical data efficiently in large OLTP databases?

A query works fine in dev but runs slow in production — what differences would you check?

How do you implement audit triggers for changes on critical tables?

Describe a time when you had to resolve a blocking chain during peak hours.

A batch job’s performance degrades every month — what could be causing it?

How do you monitor disk space growth in SQL Server?

How would you design a time-series data storage solution?

How do you optimize a query performing frequent text searches?

Explain indexed computed columns with real example.

How would you handle schema drift in ETL processes?

A process updates millions of rows daily — how do you minimize transaction log growth?

How do you mask sensitive data in non-production environments?

How do you implement optimistic concurrency in stored procedures?

How do you bulk-load data while maintaining referential integrity?

How do you monitor and control SQL Server tempdb growth?

How do you handle GDPR/PII data compliance in your databases?

A production database is growing too fast; what would you investigate?

How do you implement partition switching for ETL processes?

🔹 Tools & Best Practices
What DMVs do you commonly use for performance diagnostics?

How do you use SQL Profiler vs. Extended Events?

How do you set up database mail for alerts?

What is Query Store? How does it help performance tuning?

How do you automate database maintenance tasks?

How do you implement database-level compression?

What are the differences between simple, full, and bulk-logged recovery models?

What are linked servers? How do you secure them?

What tools do you use for schema comparison or deployment automation?

How do you manage connection pooling issues in high-volume apps?

----------------------------------------------------------------------
Data Engineer ki best job ka target hai, toh sirf MSSQL nahi, aapko ye cheezein bhi aani chahiye (main ek checklist deta hoon):

✅ SQL & Data Warehousing (✔️ mostly covered)

Complex SQL, performance tuning

Data modeling (star/snowflake schemas)

Partitioning, indexing strategies

Handling TB-scale data

✅ ETL & Data Pipelines

SSIS, Azure Data Factory, or Airflow

Building and monitoring pipelines

Data ingestion from multiple sources (files, APIs, CDC)

✅ Big Data & Cloud Platforms

Azure Synapse / AWS Redshift / Snowflake basics

Spark or Databricks familiarity is very valuable

Data Lake concepts (e.g., Delta Lake, S3, ADLS)

✅ Programming for Data Engineering

Python (pandas, pyodbc, sqlalchemy) or Scala basics

Writing ETL scripts, data transformations

Data quality and validation automation

✅ DevOps & Orchestration

CI/CD for data pipelines

Version control for SQL/ETL scripts

Monitoring & alerting tools (Grafana, CloudWatch)

✅ Soft Skills & Real-World Scenarios

Designing scalable data architectures

Explaining design decisions clearly

Balancing cost/performance in cloud

Stakeholder communication

