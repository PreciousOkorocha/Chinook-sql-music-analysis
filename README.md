# Chinook-sql-music-analysis
Exploratory SQL analysis of music store data to identify key revenue drivers, customer trends, and product performance.
# 🎵 Music Store Data Analysis (Chinook Database)

## 📊 AnalystLab Africa Data Analytics Internship — Week 3 SQL Project

---
## 📌 Project Overview

This project analyzes the **Chinook Music Store Database** using SQL Server to extract meaningful business insights from customer, sales, artist, album, and genre data.

The goal was to go beyond data querying and uncover patterns in revenue, customer behavior, and product performance to support business decision-making.

---

## 🧠 Problem Statement

The analysis was designed to answer key business questions:

- Who are the highest-spending customers?
- Which countries generate the most revenue?
- Which music genres perform best?
- Which artists generate the highest sales?
- What revenue trends can be observed over time?

---

## 🗄️ Dataset Overview

The Chinook database is a sample music store database containing relational tables such as:

- Customers  
- Invoices  
- Invoice Lines  
- Tracks  
- Albums  
- Artists  
- Genres  

These tables are connected through primary and foreign key relationships, enabling complex SQL-based analysis using joins.

---

## 🛠️ SQL Skills Used

This project demonstrates practical application of:

- SELECT statements  
- WHERE clauses  
- ORDER BY  
- GROUP BY & HAVING  
- Aggregate functions (SUM, AVG, COUNT)  
- INNER & LEFT JOINS  
- Subqueries  
- Window Functions (ROW_NUMBER, RANK, PARTITION BY)  

---

## 📊 Key Business Insights

### 1. Revenue Performance
- Total Revenue: **$2,328.60**
- Average Invoice Value: **$5.65**
- Total Transactions: **1,770**

👉 Revenue is driven by high-volume, low-value transactions, indicating strong reliance on repeat purchases.
<img width="1866" height="1024" alt="Total Revenue Analysis" src="https://github.com/user-attachments/assets/0cae20b3-660d-4b1b-aa39-da12229a0798" />

---

### 2. Revenue by Country
- Highest revenue comes from the **USA (523.06)** and **Canada (303.96)**
- France and Brazil follow closely
- Other countries contribute significantly less revenue

👉 Revenue is highly concentrated in a few key markets, showing a long-tail distribution.
<img width="1834" height="1044" alt="Rev by Country week 3" src="https://github.com/user-attachments/assets/e6fa9e18-52eb-4f91-a8cb-4b81593f1193" />

---

### 3. Top Customers
- Top customers generate similar revenue levels (42–50 range)
- No dominant VIP customers identified

👉 Customer value is evenly distributed across the customer base.
<img width="1856" height="1058" alt="Top 10 customers week 3" src="https://github.com/user-attachments/assets/a48dfc05-3a2d-47f6-a2ce-c99a8619a507" />

---
### 4. Best-Selling Genres
- Rock dominates with **835 sales**
- Followed by Latin (386), Metal (264), and Alternative & Punk (244)

👉 Music consumption is heavily skewed toward Rock.
<img width="1850" height="1048" alt="Best selling genres week 3" src="https://github.com/user-attachments/assets/b4e7bb33-53f2-4dba-8a5f-011b79a9fb53" />

---
### 5. Top Performing Artists
- Iron Maiden leads with **140 sales**
- Followed by U2 (107) and Metallica (91)

👉 Sales are concentrated among popular rock artists.
<img width="1842" height="1038" alt="Top Artists week 3" src="https://github.com/user-attachments/assets/207f8a56-f43f-4659-b3a3-01d7c98220f4" />

---
### 6. Revenue Trend Analysis
- Revenue remains relatively stable with minor fluctuations over time

👉 Trend analysis supports forecasting and business planning.
<img width="1834" height="1040" alt="Revenue trend analysis chinook week 3" src="https://github.com/user-attachments/assets/d3411016-6f8f-48e4-aa32-961ece64a643" />

---
## ⚙️ Advanced SQL Techniques Applied

- **Joins:** Combined multiple tables for customer and sales analysis  
- **Subqueries:** Identified above-average performance segments  
- **Window Functions:** Ranked customers and artists without losing row-level detail  

---

## 📌 Key Insights Summary

- Revenue is highly concentrated in a few countries (USA, Canada, France, Brazil)  
- Customer spending is evenly distributed with no VIP segment  
- Rock is the dominant genre across all sales  
- A small number of artists drive most revenue  
- The business follows a clear **Pareto (80/20) distribution pattern**  

---

## 📈 Business Recommendations

- Focus on top-performing markets (USA, Canada, France, Brazil)  
- Increase customer value through bundling and recommendations  
- Strengthen Rock as the core revenue driver  
- Expand selectively into Metal and Latin genres  
- Reduce risk by diversifying beyond key markets  

---

## 🧾 Conclusion

This project demonstrates how SQL can be used to transform raw transactional data into actionable business insights.

The analysis highlights key patterns in revenue distribution, customer behavior, and product performance, providing a foundation for data-driven decision-making.

---

## 🚀 Tools Used

- SQL Server  
- Chinook Database  
- SQL (Joins, Aggregations, Window Functions)

---
## 📌 Author

**Precious Okorocha**  
