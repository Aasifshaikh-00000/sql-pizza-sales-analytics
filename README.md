# pizza-sales-SQL-analysis

## 📘 Project Overview

This project explores a Pizza Sales Database to analyze sales performance, popular pizza types, and revenue insights using SQL.
It’s designed as a hands-on project to practice SQL queries such as JOINs, GROUP BY, ORDER BY, aggregation functions, and CTEs.

The project aims to answer real business questions and uncover useful insights from sales data.

### 🧩 Database Structure
The database contains 4 related tables:

### Table	Description
orders	Stores basic order information (order_id, date, time)
order_details	Links each order to pizzas and quantity sold
pizzas	Contains pizza details such as size and price
pizza_types	Contains pizza names, categories, and ingredients

### Schema Overview:

orders ──< order_details >── pizzas >── pizza_types

### 🧠 Objectives
The main objective is to showcase sql skills.

The project focuses on answering key business questions.
All questions are listed in the attached questions_list.txt file.

### 🧮 Tools & Concepts Used
SQL Concepts: Joins, Aggregations, Group By, CTEs, Subqueries

Database: MySQL
Visualization: Results exported and visualized using Canva document

### 📂 Project Files
File Name	Description
pizza_sales_queries.sql	SQL queries used for the analysis
orders.csv	Orders dataset
order_details.csv	Order details dataset
pizzas.csv	Pizza details dataset
pizza_types.csv	Pizza type dataset
questions_list.txt	List of all analytical questions covered
Pizza_Sales_Report.pdf	(Optional) Final report / Canva presentation

### 🚀 How to Use

Download the datasets and .sql file.
Create a new database (e.g., pizza_sales_db).
Import the CSV files into your database.
Run the queries from pizza_sales_queries.sql.
Explore and modify queries to find more insights!

### 🧑‍💻 Author
Aasif Shaikh
