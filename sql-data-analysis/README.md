# SQL Data Analysis

## Overview
This project focuses on using SQL to extract, analyze, and transform data to answer business questions.

## Business Problem
Organizations rely on data stored in databases, but without proper querying, it is difficult to extract meaningful insights. This project demonstrates how SQL can be used to solve real business problems.

## Tools Used
- SQL

## Skills Demonstrated
- Data extraction
- Joins (INNER, LEFT)
- Aggregations (SUM, COUNT, AVG)
- Filtering and grouping
- Data transformation

## Example Queries

### 1. Total Orders by Restaurant
SELECT restaurant_id, COUNT(*) AS total_orders
FROM orders
GROUP BY restaurant_id;

### 2. Average Order Value
SELECT AVG(order_amount) AS avg_order_value
FROM orders;

### 3. Revenue by Category
SELECT category, SUM(order_amount) AS total_revenue
FROM orders
GROUP BY category;

## Business Insight
SQL enables efficient data analysis by allowing businesses to quickly retrieve and aggregate large datasets for decision-making.
