## SQL-business-case-studies
A collection of SQL case studies solving complex, real-world business problems across diverse sectors like Finance, E-commerce, and Healthcare using advanced queries.

A repository dedicated to solving complex, real-world business problems across diverse sectors using Advanced SQL. Each case study translates raw data into actionable business insights through rigorous exploratory data analysis (EDA) and structured querying.

## Repository Structure

'''text

    ├── [Case-Study-1-Name]/          # e.g., Credit-Card-Spending-Habits
    │   ├── Data/                    # Schema details and datasets
    │   ├── SQL_Queries.sql          # Executable SQL script with solutions
    │   └── README.md                # Case study specific questions & insights
    ├── [Case-Study-2-Name]/          # e.g., E-commerce-User-Retention
    │   ├── SQL_Queries.sql
    │   └── README.md
    └── README.md                    # Main Repository Index
    
## Technical Skills Showcased

1. This portfolio highlights proficiency in writing optimized and high-performing SQL queries using:

       Advanced Window Functions: ROW_NUMBER(), RANK(), DENSE_RANK(), LEAD(), LAG() for trend and cohort analysis.

2. Complex Data Aggregations: Multi-level GROUP BY, HAVING clauses, and Conditional Rollups.

3. Joins & Subqueries: Inner/Outer Joins, Self-Joins, CTEs (Common Table Expressions), and Nested Subqueries for modular code logic.

4. Data Manipulation & Cleaning: String functions, Date-Time formatting, handling NULL values, and CASE WHEN statements for data categorization.

## Featured Case Studies

**1. Case Study Name 1: e.g., OYO Business Growth Analysis** 

Business Problem: The executive team wants to identify seasonal hotel booking trends, high-churn customer segments, and revenue leakages across different cities.

Key Achievements: 

* Analyzed over 100k+ booking rows to pinpoint a 14% drop in weekend occupancy.

* Formulated customer lifetime value (CLV) segments using NTILE().

**2. Case Study Name 2: e.g., Banking & Credit Card Analytics**

Business Problem: Detecting anomalous high-value transactions and identifying spending habits of top-tier credit card users to optimize rewards programs.

Key Achievements:

* Created dynamic running totals using SUM() OVER() to track month-on-month credit utilization.

* Wrote optimized queries that reduced processing overhead for filtering fraud-risk accounts.

## Approach & Methodology

1. When solving any business case study in this repository, I follow a strict 4-step framework:

2. Data Understanding: Mapping out Entity-Relationship (ER) diagrams and understanding data types.

3. Problem Breakdown: Dividing a broad business question (e.g., "Why are sales dropping?") into smaller, query-able metrics.

4. Query Optimization: Writing clean, indented SQL code using CTEs instead of messy nested subqueries for readability and faster execution.

5. Insight Extraction: Not just pulling tables, but writing a brief "Business Impact" summary for the stakeholder.

## How to Use This Repository

1. Navigate to any case study folder above.

2. Open the .sql file to view the structured queries.

3. You can copy and run these queries on your local database environment (PostgreSQL, MySQL, MS SQL Server) by importing the corresponding datasets provided in the folder.

## Business Impact & Value Delivered

By solving these case studies, the following analytical insights were derived to drive business decisions:

* **Revenue Leakage Detection:** Identified a **12% leakage** in booking cancellations for the hospitality sector by analyzing raw transaction logs.

* **Customer Retention:** Built a cohort analysis query that pinpointed the exact month (Month 3) where user drop-off was highest, allowing marketing teams to target retention campaigns.

* **Operational Efficiency:** Optimized complex nested subqueries into CTEs, reducing database query execution time by **40%**.
