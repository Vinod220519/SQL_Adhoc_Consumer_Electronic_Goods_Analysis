# SQL_Adhoc_Consumer_Electronic_Goods_Analysis

# 💰 Finance & Supply Chain Analytics SQL Project

## 📊 Project Overview

This **Finance & Supply Chain SQL project** focuses on real-world business problems faced by a fictional company, **AtliQ Hardwares**, using SQL-based ad hoc analytics. The project demonstrates how SQL queries and stored procedures can be used to derive actionable insights in finance and supply chain domains.

Data is sourced from a structured MySQL database simulating business operations such as pricing, sales, discounts, and forecasting. The project answers real-world business questions and supports data-driven decisions.

---

## 🌟 Objectives

1. **Understand Business Model** – Explore AtliQ's multi-channel distribution strategy.
2. **Finance Analytics** – Calculate net sales, discounts, and customer revenue performance.
3. **Supply Chain Insights** – Analyze forecast accuracy. 
4. **Stored Procedures** – Create reusable SQL procedures for recurring analysis tasks.
5. **Performance Optimization** – Use views, indexes, and joins to improve query speed.
6. **Data Validation** – Cross-check joins, fiscal calculations, and customer hierarchies.

---

## 🧠 Key SQL Queries Used

* Calculate **monthly gross revenue** for a customer 
* Summarize **aggregated monthly gross sales**
* Classify **markets as Gold/Silver** based on sales volume
* Identify **top markets by net sales**
* Calculate **net invoice sales** after applying pre- and post-invoice discounts
* Determine **top customers** in each market
* Rank **top-selling products by quantity and revenue**
* Generate **region-wise revenue breakdowns**
* Create **forecast accuracy reports** per customer

---

## 📂 Dataset Tables Used

* **dim\_customer** – Customer metadata (market, region, platform)
* **dim\_product** – Product hierarchy (division, segment, category, variant)
* **dim\_date** – Calendar to fiscal mapping
* **fact\_sales\_monthly** – Actual sales quantity per product/customer
* **fact\_gross\_price** – Gross price per product per year
* **fact\_pre\_invoice\_deductions** – Discounts before invoice
* **fact\_post\_invoice\_deductions** – Promotions/rebates applied after invoice
* **fact\_forecast\_monthly** – Forecasted quantity per product/customer
* **Views/Procedures** – `net_sales`, `get_market_badge`, etc.

---

## 🛠️ Tools & Technologies

* **SQL (MySQL)** – Core language for all queries, joins, calculations
* **Stored Procedures & Views** – Modular, reusable logic
* **MySQL Workbench** – Query writing and data modeling
* **(Optional)** Excel or BI tool for visualization

---

## 📅 Realistic Business Use Cases Covered

| Area              | Use Case Example                                         |
| ----------------- | -------------------------------------------------------- |
| Finance           | Identify top revenue customers in India                  |
| Revenue Analysis  | Calculate net sales post discounts                       |
| Sales Performance | Rank top products by quantity and value                  |
| Market Strategy   | Classify markets by sales volume (Gold/Silver)           |
| Supply Chain      | Track forecast accuracy for each customer                |

---

## 📁 Repository Structure

```
├── sql_queries/
│   ├── finance_analysis.sql
│   ├── supply_chain_accuracy.sql
│   ├── top_customers_products.sql
│   └── stored_procedures.sql
├── views/
│   ├── net_sales_view.sql
│   └── sales_discount_view.sql
└── README.md (This file)
```

---


