# Python-SQL-Ecommerce-project
This project uses a real-world e-commerce dataset to perform data analysis and SQL operations. The dataset contains information about customers, sellers, products, orders, payments, and geolocations, making it ideal for practicing database design, SQL queries, and Python-based analytics.

It includes:

Relational database schema

ETL pipeline to load CSVs into SQL

Ready-to-use SQL queries for insights

Exploratory Data Analysis (EDA) with Python

A minimal Flask API to serve results

📂 Dataset

The dataset consists of multiple CSV files (real-world scale, thousands of rows):

File	Description
customers.csv	Customer ID, city, state
geolocation.csv	Zip codes with latitude & longitude
order_items.csv	Items in each order (product, seller, price, freight)
orders.csv	Order details (timestamps, status, customer)
payments.csv	Payment method, installments, amount
products.csv	Product category, size, weight, dimensions
sellers.csv	Seller details (location, ID)
🚀 Features

✅ SQL Database Schema for normalized data
✅ Data Loader Script → Load CSVs into SQLite (or MySQL/Postgres)
✅ Pre-written SQL Queries → Sales trends, top sellers, delivery times
✅ EDA with Python → Pandas, Matplotlib visualizations
✅ Flask API → Serve top products/sellers via REST endpoints

🛠️ Tech Stack

Python → Pandas, Matplotlib, SQLAlchemy, Flask

Database → SQLite (default), MySQL/PostgreSQL (optional)

Jupyter Notebook / Scripts → For analysis & visualization
