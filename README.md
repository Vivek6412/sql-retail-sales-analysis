# 🛒 Online Retail Sales Analysis Database

## 📌 Project Overview

This project is a simple SQL-based system to store and analyze retail sales data. It models how an online store can manage customers, products, and orders, and then use queries to generate useful insights from that data.

---

## 🎯 Objectives

* Design a structured relational database
* Store customer, product, and order data
* Analyze sales data using SQL queries

---

## 🧱 Database Design

The database includes the following tables:

* Customers (customer_id, name, city)
* Products (product_id, name, category, price)
* Orders (order_id, customer_id, order_date)
* Order_Items (order_id, product_id, quantity)

Foreign key relationships are used to connect the tables and maintain consistency between orders, customers, and products.

---

## ⚙️ Key Features

* Relational database design using multiple tables
* Use of JOINs to combine data across tables
* Aggregation queries using SUM and GROUP BY
* Queries to extract business insights from raw data

---

## 📊 SQL Analysis

### 🔹 Top-Selling Products

![Top Products](top_products.png)

### 🔹 Most Valuable Customers

![Valuable Customers](valuable_customers.png)

### 🔹 Monthly Revenue

![Revenue](revenue.png)

### 🔹 Category-wise Sales

![Category Sales](category_sales.png)

### 🔹 Inactive Customers

![Inactive Customers](inactive_customers.png)

---

## 📸 Database Screenshots

### 🔹 Tables Created

![Tables List](tables_list.png)

### 🔹 Table Structure

![Structure](table_structure.png)

### 🔹 Data in Tables

![Data](all_tables_data.png)

---

## 🛠️ Tools Used

* MySQL Workbench
* SQL

---

## 🚀 How to Run

1. Open MySQL Workbench
2. Run the SQL script file (`retail_project.sql`)
3. Execute the queries to view results

---

## 👤 Author

**Vivek Gupta**

* GitHub: https://github.com/Vivek6412
