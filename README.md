# E-commerce Database Setup

## Overview
This project sets up a simple e-commerce database using MySQL. It includes three main tables: `customers`, `products`, and `orders`, with additional normalization through an `order_items` table. Various SQL queries are provided to retrieve, update, and manage data efficiently.

## Database Structure

### Tables
- **customers**: Stores customer details (ID, name, email, address).
- **products**: Stores product details (ID, name, price, description, discount).
- **orders**: Stores order details (ID, customer ID, order date).
- **order_items**: Normalized table to store product-wise order details (ID, order ID, product ID, quantity, price).

## Features
- Inserts sample data for customers, products, and orders.
- Retrieves customers who placed orders in the last 30 days.
- Calculates total spending per customer.
- Updates product prices.
- Adds a `discount` column to `products`.
- Fetches the top 3 highest-priced products.
- Retrieves customer names who purchased a specific product.
- Joins tables to get customer order details.
- Filters orders based on total amount.
- Implements database normalization by introducing `order_items`.
- Computes the average total amount of all orders.

## Usage
1. **Run the SQL script** in a MySQL environment to create the database and insert sample data.
2. **Execute the queries** to perform various data operations and analysis.
3. **Modify or extend** the schema as needed for additional e-commerce features.

## Prerequisites
- MySQL installed
- Basic knowledge of SQL queries

## How to Run
1. Open a MySQL terminal or GUI (such as MySQL Workbench).
2. Copy and paste the SQL script (`ecommerce.sql`).
3. Execute queries as needed.

## Future Enhancements
- Implement stored procedures for complex queries.
- Add indexing for performance optimization.
- Introduce more relationships (e.g., categories, payment details).

This project provides a strong foundation for managing e-commerce data effectively.

