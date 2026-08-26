# 👥 Customer Behavior & Sales Analytics Dashboard

## 📊 Project Overview

An interactive Power BI dashboard developed to examine customer purchasing behavior, revenue contribution, customer segments, product performance, discount usage, and membership patterns using PostgreSQL and Power BI.

The project covers **3,901 customer transaction records** and addresses **8+ business questions** through SQL-based analysis and interactive Power BI reporting.

## 🛠️ Tech Stack

- **Power BI** — Dashboard development and visualization
- **PostgreSQL** — Data querying and business analysis
- **SQL** — CTEs, subqueries, CASE statements, aggregations, and window functions
- **Power Query** — Data transformation and preparation
- **DAX** — KPI calculations and analytical measures

## 📌 Project Metrics

 Metric  Value 
1. Customer Records          =       3,901 
2. Business Questions        =        8+ 
3. Total Revenue             =       Rs. 2.33L+ 
4. Loyal Customers           =       3,476 
5. Returning Customers       =       341 
6. New Customers             =        83 

## 🔍 Business Analysis

The dashboard covers:

- Revenue comparison by gender
- Customer segmentation based on previous purchases
- Product-level purchase performance
- Average review ratings
- Discount penetration by product
- Membership and purchasing behavior
- Repeat buyer behavior
- Category-level product performance

## 💡 Key Insights

- Male customers generated **Rs. 1.58L (67.8%)** of total revenue, compared with **Rs. 75.2K (32.2%)** from female customers.
- **3,476 customers (89.1%)** were classified as Loyal, while **341 (8.7%)** were Returning and **83 (2.1%)** were New.
- Average purchase value was **Rs. 59.49 for members** versus **Rs. 59.87 for non-members**, showing no meaningful spending uplift.
- Among repeat buyers with **5+ previous purchases**, membership adoption was **27.56%**.
- **Hat** had the highest discount penetration at **50.0%**, followed by **Sneakers (49.66%)** and **Coat (49.07%)**.
- **Gloves** recorded the highest average review rating at approximately **3.86**.

## 🧮 SQL Analysis

The PostgreSQL analysis uses:

- CTEs
- Subqueries
- CASE statements
- GROUP BY and aggregations
- Window functions
- Conditional aggregation
- Percentage calculations
- Customer segmentation

The complete SQL queries are available in:

`sql/customer_behavior_analysis.sql`

## 📸 Dashboard Preview

![Customer Behavior Dashboard](dashboard-overview.png)

## 📂 Project Files

- `Customer_Behavior_Sales_Dashboard.pbix` — Power BI dashboard
- `sql/customer_behavior_analysis.sql` — PostgreSQL analysis queries
- `dashboard-overview.png` — Dashboard preview

## ▶️ How to Use

1. Download the `.pbix` file.
2. Open it using **Power BI Desktop**.
3. Refresh or update the data source if required.
4. Use the dashboard filters and visuals to explore customer and sales behavior.

## 👤 Author

**Nishu Gupta**

[GitHub](https://github.com/Nishu84570)
