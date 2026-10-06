# E-Commerce Sales Analysis — MySQL

SQL analysis of the Olist Brazilian e-commerce dataset covering sales, customers, products, and delivery performance.

## Key Findings

| Area | Finding |
|---|---|
| Top market | **São Paulo** was the largest state market at **38.28%** of total sales (**R$5.20M**) |
| Top category | **Health & Beauty** was the top product category at **9.26%** of sales (**R$1.26M**) |
| Customer retention | **96.88%** of customers made only one purchase, so repeat buying is very low |
| Fulfillment | **97.02%** of orders were successfully delivered, with an average delivery time of **12.1 days** |

**Takeaway:** Sales are concentrated in a single state, and almost all customers buy once. Retention (for example post-purchase follow-ups or loyalty offers) looks like the biggest growth opportunity.

## Dataset

[Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

| Table | Records |
|---|---|
| Orders | 99,441 |
| Unique customers | 96,096 |
| Products | 32,951 |
| Order items | 112,650 |

Four related tables are used: `customers`, `orders`, `products`, and `order_items`.

## Tools

- MySQL 8.0
- SQL

## SQL Skills Demonstrated

- `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`
- `JOIN`s across four tables
- `SUM`, `COUNT`, `AVG`
- `CASE` statements
- CTEs
- `CREATE VIEW`

## Analysis Performed

- Total sales, total orders, total customers, and average order value
- Monthly sales trends
- Sales by customer state
- Top product categories and top products by sales
- Average item price by category
- Order status distribution
- Average delivery time
- Order performance classification using `CASE`
- Monthly sales analysis using a CTE
- Customer order frequency
- Reusable SQL view (`vw_sales_analysis`) combining customer, order, product, and transaction data for Power BI reporting

## How to Run

1. Download the Olist dataset and copy the four CSV files (customers, orders, products, order items) into your MySQL uploads folder.
2. Open `ecommerce_sales_analysis.sql` in MySQL Workbench.
3. Update the file paths in the `LOAD DATA INFILE` statements if your uploads folder differs.
4. Run the script from top to bottom. It creates the `ecommerce_sales` database, loads the tables, runs the analysis queries, and creates the view.

## Project Structure

```
ecommerce-sales-analysis-sql/
├── README.md
└── ecommerce_sales_analysis.sql
```

## Author

**Priyam Ojha** — [LinkedIn](https://www.linkedin.com/in/priyamojha) | [GitHub](https://github.com/priyamojha45-gif)
