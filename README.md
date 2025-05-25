# 📊 Sales Insights SQL Project

This project presents a hands-on SQL data analysis case study based on a fictional retail company’s sales data. It demonstrates my ability to model business processes into a normalized database structure, write optimized SQL queries, and extract actionable insights that can help guide decision-making.

---

## 🧾 Overview

A mid-sized retail company is looking to improve sales performance and customer retention. To support this, I designed a relational database schema to capture relevant business data (customers, products, transactions, and employees), populated it with realistic sample data, and answered key business questions using SQL.

This project highlights a data analyst’s role in **translating raw data into strategic insights**.

---

## 🗂️ Database Design

The schema consists of five core tables:

- **CUSTOMER**: Stores customer details including name, location, and region.
- **PRODUCT**: Catalog of products with attributes such as category, price, and weight.
- **SALESPERSON**: Sales team roster with role, territory, and joining information.
- **SALES**: Primary transactional table capturing individual orders.
- **SALES_HISTORY**: Snapshot of historical orders (backup/archive).

---

## 🧰 Tools & Technologies

- **SQL** (MySQL)
- **Version Control**: Git & GitHub

---

## 📈 Entity Relationship Diagram (ERD)

The ERD visually represents the relationships among entities in the database.

![ERD](./images/erd_sales_project.png)

---

## 💼 Business Questions Answered

Below are key business questions answered using SQL, along with the features used and the insights derived:

| 💡 Business Question                         | 🔍 SQL Techniques Used      | 📊 Insight |
|---------------------------------------------|-----------------------------|------------|
| Which region is contributing the most revenue? | `JOIN`, `GROUP BY`, `SUM()` | Southern region leads in total sales |
| What are the top 5 products by revenue?     | `ORDER BY`, `LIMIT`         | iPhone, HTC 7800, Samsung F7100 are top performers |
| How are monthly revenues trending?          | `DATE_FORMAT`, `GROUP BY`   | Sales peak observed in February |
| Who are the top-performing salespeople?     | `JOIN`, `GROUP BY`, `SUM()` | Bob Moris and Peter Mann lead |
| Which customers generate the highest revenue? | `GROUP BY`, `SUM()`         | Key customers identified for loyalty program |
| Which product categories are driving sales? | `JOIN`, `GROUP BY`          | Mobile category contributes the most |
| What is the average order value?            | `AVG()`                     | Useful for upselling and pricing strategy |
| How many repeat customers do we have?       | Subqueries, `HAVING COUNT > 1` | 30% of customers made multiple purchases |
| Are any products frequently bought together? | Self `JOIN`, `GROUP BY`     | Product bundling opportunities identified |
| Can we identify successful product pairings? | Aggregation + filtering     | iPhone & Mobile Cover most common combo |

---

## 🧠 Advanced SQL Techniques Demonstrated

This project goes beyond basic SQL and incorporates:

- **Common Table Expressions (CTEs)** for improved query readability.
- **Window Functions** like `RANK()` to identify top-N performance metrics.
- **Views** to encapsulate and reuse complex logic.
- **Stored Procedures** to automate report generation and maintenance tasks.
- **Data validation and integrity checks** built into schema design.

---
