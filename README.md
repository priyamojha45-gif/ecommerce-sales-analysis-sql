# E-Commerce Sales Analysis — SQL + Power BI

## Objective
Analyze Brazilian e-commerce sales data using MySQL and prepare a clean dataset for Power BI.

## Tools
- MySQL 8.0
- Power BI
- SQL

## SQL skills demonstrated
SELECT, WHERE, GROUP BY, ORDER BY, JOIN, SUM, COUNT, AVG, CASE, CTEs, CREATE VIEW.

## Dashboard KPIs
- Total Sales
- Total Orders
- Total Customers
- Average Order Value

## Suggested Power BI visuals
1. Monthly Sales Trend
2. Sales by Customer State
3. Top 10 Product Categories
4. Order Status Distribution
5. Top 10 Products
6. Table of category performance

## How to run
1. Copy these four CSVs into:
   C:/ProgramData/MySQL/MySQL Server 8.0/Uploads/
   - olist_customers_dataset.csv
   - olist_orders_dataset.csv
   - olist_products_dataset.csv
   - olist_order_items_dataset.csv

2. Open MySQL Workbench.
3. Open `ecommerce_sales_analysis.sql`.
4. Run the script.
5. The script creates the database, tables, imports data, runs analysis queries, and creates `vw_sales_analysis`.
6. In Power BI, connect to MySQL and select `ecommerce_sales.vw_sales_analysis`.

## Resume project title
E-Commerce Sales Analysis Dashboard | MySQL, Power BI, DAX

## Resume bullets
- Analyzed e-commerce transaction data using MySQL to identify sales trends, customer behavior, product performance, and order patterns.
- Used SQL joins, aggregations, CASE statements, and CTEs to transform and analyze multi-table transactional data.
- Created a Power BI-ready SQL view for interactive reporting of sales, orders, customers, product categories, and regional performance.
