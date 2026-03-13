🛒 Retail Sales Data Warehouse — Superstore Dataset
An end-to-end Data Engineering project that transforms a flat retail CSV file into a structured star schema data warehouse in MySQL, with 20+ SQL analytics queries covering business insights on sales, profit, customers, and regional performance.
-------------------------------------------------------------------------------------------------------------
📌 Project Overview
This project was built to demonstrate real-world data engineering skills — taking raw messy data, cleaning it, designing a proper warehouse schema, loading it to MySQL, and deriving business insights using advanced SQL.
Dataset: Superstore Sales Dataset (Kaggle)
Records: 9,994 retail transactions
Period: 2014 — 2017

-------------------------------------------------------------------------------------------------------------
🏗️ Architecture
Raw CSV File (store_data.csv)--> Python + Pandas (cleaning & transformation)-->Star Schema Design (5 tables)-->MySQL Database (superstore_db)-->SQL Analytics Queries (20+ queries)

-------------------------------------------------------------------------------------------------------------
⭐ Star Schema Design
fact_orders is the central table connected to:
- data_customers
- data_products  
- data_location
- data_dates

-------------------------------------------------------------------------------------------------------------
🔧 Tech Stack

Python — Core ETL logic
Pandas — Data cleaning and transformation
MySQL — Data warehouse storage
SQLAlchemy — Python to MySQL connection
Jupyter Notebook — Interactive development
Git & GitHub — Version control

-------------------------------------------------------------------------------------------------------------
📊 SQL Analytics Queries

-->
Top 10 customers by total revenue
Profit margin percentage by category
Monthly sales trend year wise
Top 10 states by total sales
Loss making products with negative total profit is negative
Total orders per year
Which ship mode is used most  
Most used ship mode
Sub-category with highest quantity sold

-->
Month over month revenue growth using LAG()
Best performing category per region using DENSE_RANK() with PARTITION BY
Running total of sales within each year using SUM() OVER()
Top 3 customers per segment using ROW_NUMBER() with PARTITION BY
Rank products by profit within each category using RANK() with PARTITION BY
Products with above average profit using subquery

-------------------------------------------------------------------------------------------------------------

👤 Author
Sourabh Guleria

GitHub: github.com/sourabh-py-001
Email: sourabh.guleria.py@gmail.com