# Sales Insights SQL Project

This project is designed to showcase SQL skills for a Data Analyst role using a realistic business scenario. It includes data modeling, schema design, data population, and exploratory SQL queries on sales transactions.

## 🧾 Project Overview

A retail company wants to analyze their sales data for decision-making. The project involves multiple tables representing customers, products, salespersons, sales transactions, and sales history.

## 🗂️ Database Schema

- **CUSTOMER**: Information about customers (ID, name, address, region).
- **PRODUCT**: List of products with category, price, size, and weight.
- **SALESPERSON**: Sales team data including role and region.
- **SALES**: Transactional sales records.
- **SALES_HISTORY**: Archival or previous sales records.

## ⚙️ Technologies Used

- SQL (MySQL)
- Entity-Relationship (ER) modelling
- Data manipulation and query writing


# 📊 SQL Sales Analytics Project

This project is a comprehensive SQL-based analysis of a fictional company's sales data. It is designed to showcase real-world **data analysis**, **business intelligence**, and **advanced SQL skills** including joins, aggregations, window functions, views, and stored procedures.

---

## 🔧 Tools & Technologies

- SQL (MySQL compatible)
- ERD design tools (drawSQL.io / dbdiagram.io)
- GitHub for version control
- Optional: Tableau / Power BI (for dashboard layer)

---

## 🧠 Objective

To simulate a business scenario involving **customers**, **products**, **salespeople**, and **transactions**, and solve real business questions using SQL to extract insights.

---

## 📁 Database Schema

- **CUSTOMER**
- **PRODUCT**
- **SALES**
- **SALES_HISTORY**
- **SALESPERSON**

See the ERD below 👇

---

## 📈 Entity Relationship Diagram (ERD)

![ERD](./images/erd_sales_project.png)

---

## 🔍 Business Questions Solved

| Question                                   | SQL Feature           | Outcome |
|---------                                   |-------------          |---------|
| Which region generates the most revenue?   | GROUP BY, JOIN        | SOUTH region performs best |
| Top 5 products by revenue?                 | ORDER BY + LIMIT      | Focus on iPhone, HTC, etc. |
| Monthly revenue trend?                     | DATE_FORMAT, GROUP BY | Peak in February |
| Top salespeople?                           | JOIN + SUM            | BOB MORIS leads |
| High-value customers?                      | COUNT + SUM           | Targeted loyalty |
| Category-wise revenue?                     | GROUP BY + JOIN       | Mobiles lead |
| Average Order Value?                       | AVG()                 | Used for upsell targeting |
| Repeat customers?                          | Subquery + HAVING     | 30% customer retention |
| Product bundling?                          | Self JOIN             | iPhone & cover bundled |
| Product pair combos?                       | COUNT + GROUP         | Target cross-sells |

---

## 🔑 Key SQL Features Used

- ✅ JOINs and aggregations
- ✅ Window functions (`RANK`)
- ✅ CTEs (Common Table Expressions)
- ✅ Views for reusable logic
- ✅ Stored procedures for automation

---

## 📂 Project Structure

sales-analytics-sql/
├── data/
│   ├── create\_tables.sql
│   ├── insert\_data.sql
│   └── sample\_queries.sql
├── advanced/
│   ├── window\_functions.sql
│   ├── views.sql
│   └── stored\_procedures.sql
├── images/
│   └── erd\_sales\_project.png
├── README.md
