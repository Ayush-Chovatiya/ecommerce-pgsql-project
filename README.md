# E-Commerce Database Project (PostgreSQL)

## Overview
This project shows how to design and implement a relational database for an
e-commerce application using PostgreSQL. The database supports common
e-commerce features such as users, products, orders, carts, payments, and
reviews.

The goal of this project is to demonstrate good database design practices
and the ability to write useful SQL queries for business analysis.

---

## Database Schema
The database is created under a schema named `ecommerce`. The tables are
normalized to reduce data duplication and maintain data consistency.

### Tables
- users – stores customer and admin information
- categories – stores product categories
- products – stores product details and stock information
- carts – stores shopping cart data for users
- cart_items – stores products added to carts
- orders – stores customer order details
- order_items – stores products included in each order
- payments – stores payment information
- reviews – stores customer ratings and comments

---

## Key Features
- Normalized relational database design
- Primary key and foreign key relationships
- CHECK constraints for data validation
- Queries for reporting and analysis

---

## Technologies Used
- PostgreSQL
- pgAdmin
  
---

## SQL Queries
The `queries.sql` file contains queries for:
- Customer and order analysis
- Revenue calculation
- Product sales performance
- Inventory monitoring
- Review and rating analysis

These queries use joins, aggregations, subqueries.

---

## Project Structure
```text
ecommerce-postgresql-project/
├── schema.sql
├── queries.sql
└── README.md
```

---

## How to Run
1. Create a PostgreSQL database
2. Run `schema.sql` to create the tables
3. (Optional) Insert sample data
4. Run queries from `queries.sql`

---

## Learning Outcomes
- Designed a complete e-commerce database schema
- Used PostgreSQL constraints to enforce data rules
- Wrote SQL queries for real-world use cases
- Improved understanding of relational databases
