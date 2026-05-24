# 📊 Advanced SQL Data Analytics Project

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Advanced-orange?style=for-the-badge)

## 🎯 Project Overview
Advanced SQL analysis on a retail Data Warehouse using **Window Functions, CTEs, Subqueries, and Reporting Views** to answer real business questions about sales trends, customer behavior, and product performance.

This project builds on the EDA foundation (Project 1) and moves into deeper analytical techniques used in professional data analytics environments.

## 📖 Full Documentation & Screenshots
👉 **[Click here to view complete project documentation on Notion](https://www.notion.so/Project-2-Advanced-SQL-Data-Analysis-36a6a1bbb6e480259a58c775c34dcad9?source=copy_link)**

---

## 🗺️ Analysis Roadmap

| # | Analysis Type | Business Question Answered |
|---|---|---|
| 07 | Change-Over-Time | How have sales trended over years and months? |
| 08 | Cumulative Analysis | What is the running total and moving average price over time? |
| 09 | Performance Analysis | Which products are above/below average and growing/declining? |
| 10 | Part-to-Whole | Which categories contribute the most to total revenue? |
| 11 | Data Segmentation | How are customers and products distributed across segments? |
| 12 | Reporting | What are the full KPI profiles for customers and products? |

---

## 💡 Key Findings

- 📈 **2013 was the peak year** — generating $16.3M, representing 55.7% of total revenue
- 📉 **Average price declined 46%** over 4 years — from $3,101 to $1,668
- 🚲 **Bikes generate 96.46%** of all revenue — extreme category concentration
- 👥 **79.1% of customers are New** — retention is the #1 growth opportunity
- ⭐ **VIP customers (8.9%)** are the highest-value segment with 12+ months history and $5,000+ spending

---

## 🛠️ SQL Techniques Used

| Technique | Used For |
|---|---|
| `Window Functions` | Running totals, moving averages, LAG() |
| `CTEs` | Multi-layer query organization |
| `PARTITION BY` | Per-product and per-customer calculations |
| `LAG()` | Year-over-year performance comparison |
| `DATETRUNC / FORMAT` | Time-based grouping and trend analysis |
| `CASE WHEN` | Customer and product segmentation |
| `CREATE VIEW` | Reusable reporting layer |
| `Subqueries` | Nested calculations |

---

## 📁 Scripts

| File | Description |
|---|---|
| `07_change_over_time_analysis.sql` | Yearly and monthly sales trends |
| `08_cumulative_analysis.sql` | Running totals and moving average |
| `09_performance_analysis.sql` | Product performance vs average and prior year |
| `10_part_to_whole_analysis.sql` | Category revenue contribution % |
| `11_data_segmentation.sql` | Customer and product segmentation |
| `12_report_customers.sql` | Customer KPI reporting view |
| `12_report_products.sql` | Product KPI reporting view |

---

## 🗄️ Database

| Table | Rows | Description |
|---|---|---|
| gold.dim_customers | 18,484 | Customer dimension |
| gold.dim_products | 295 | Product dimension |
| gold.fact_sales | 60,398 | Sales transactions |

---

## 🛠️ Tools Used
- Microsoft SQL Server 17
- SQL Server Management Studio (SSMS)
- Notion (Documentation)

---

## 🔗 Related Project
👉 [Project 1 — SQL Exploratory Data Analysis (EDA)](https://www.notion.so/Project-1-SQL-EDA-3686a1bbb6e4807796eef5f9f8693ea3?source=copy_link)
Advanced SQL project analyzing sales trends, revenue concentration,  customer behavior (VIP/Regular/New), and product performance  using CTEs, Window Functions, and reporting Views | SQL Server
