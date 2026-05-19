# SQL Analytics Projects

## Project Overview
This repository contains SQL projects focused on data analysis, business intelligence, reporting, and database querying.

The projects demonstrate practical SQL skills used in real-world business analytics environments.

---

# Skills Demonstrated

- SQL Queries
- Joins
- Aggregations
- Group By
- Subqueries
- Window Functions
- Common Table Expressions (CTEs)
- Data Cleaning
- Business Reporting
- KPI Analysis

---

# Tools Used

- MySQL
- SQL Server
- PostgreSQL
- Excel
- Power BI

---

# Featured SQL Projects

## 1. Sales Performance Analysis

### Objectives
Analyze sales trends, profitability, and customer performance.

### SQL Concepts Used
- INNER JOIN
- GROUP BY
- SUM()
- AVG()
- CASE WHEN
- ORDER BY

### Business Insights
- Identified top-performing products
- Analyzed regional profitability
- Evaluated customer purchase trends

---

## 2. Customer Analytics Dashboard Dataset

### Objectives
Prepare analytical datasets for Power BI dashboards.

### SQL Concepts Used
- Data Cleaning
- CTEs
- Window Functions
- Ranking Functions

### Business Insights
- Segmented customers
- Created KPI-ready datasets
- Improved reporting efficiency

---

## 3. Inventory and Supply Chain Analysis

### Objectives
Analyze stock levels, inventory movement, and operational performance.

### SQL Concepts Used
- Joins
- Aggregate Functions
- Date Functions
- Subqueries

### Business Insights
- Identified low-stock products
- Improved inventory visibility
- Analyzed warehouse performance

---

# Sample SQL Query

```sql
SELECT 
    Region,
    SUM(Sales) AS Total_Sales,
    SUM(Profit) AS Total_Profit
FROM Orders
GROUP BY Region
ORDER BY Total_Sales DESC;
