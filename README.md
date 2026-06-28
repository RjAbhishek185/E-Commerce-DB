# 🛒 E-Commerce Database Management & SQL Analysis

> **Week 2 Assignment – Celebal Summer Internship 2026**

## 📖 Overview

This repository contains my Week 2 internship assignment focused on designing and analyzing an e-commerce database using **MySQL**. The project demonstrates the implementation of relational database concepts and SQL techniques to manage and analyze sales data.

The database models an online shopping system with customers, products, orders, and order items, enabling business-oriented analysis through SQL queries.

---

## 🎯 Project Objectives

* Design a relational e-commerce database.
* Implement Primary Key and Foreign Key relationships.
* Apply database constraints to maintain data integrity.
* Perform filtering and sorting using SQL.
* Analyze business data with aggregate functions.
* Combine data using different types of JOINs.
* Improve query performance through indexing.
* Execute transactions while maintaining ACID properties.

---

## 🗃️ Database Tables

The project consists of the following tables:

| Table       | Description                            |
| ----------- | -------------------------------------- |
| Customers   | Stores customer information            |
| Products    | Stores product details                 |
| Orders      | Stores order information               |
| Order_Items | Stores products included in each order |

### Database Relationships

```text
Customers
    │
    └── customer_id
            │
            ▼
         Orders
            │
            └── order_id
                    │
                    ▼
              Order_Items
                    ▲
                    │
              product_id
                    │
                 Products
```

---

## 💻 Technologies Used

* MySQL 8.0
* SQL
* GitHub

---

## 📁 Repository Structure

```text
E-Commerce-DB/
|
│ ├── README.md
|
│ ├── sql/
│    ├── schema.sql
│    ├── insert_data.sql
│    └── queries.sql
|
│ ├── outputs/
│    ├── Section_A.md
│    ├── Section_B.md
│    ├── Section_C.md
│    ├── Section_D.md
│    └── Section_E.md
|
│ └── screenshots/
|   
└── Dataset/
│ └── superstore.csv
```

---

## 🚀 Getting Started

### 1. Create the Database

```sql
CREATE DATABASE superstore;
USE superstore;
```

### 2. Import the SQL Files

Execute the SQL files in the following order:

1. Database Schema
2. Sample Data
3. SQL Queries

---

## 📚 Assignment Contents

### Section A

* Basic SQL Queries
* SELECT Statement
* DISTINCT
* Primary Keys
* UNIQUE Constraint
* CHECK Constraint

### Section B

* WHERE Clause
* BETWEEN
* Data Filtering
* Indexes
* Query Optimization
* SARGable Queries

### Section C

* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()
* GROUP BY
* HAVING
* ORDER BY

### Section D

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* Multi-table JOINs
* Foreign Keys
* Table Relationships

### Section E

* CASE Statement
* Conditional Aggregation
* Transactions
* COMMIT
* ROLLBACK
* ACID Properties

---

## 📊 Business Analysis Performed

This project answers several practical business questions, including:

* Total revenue from delivered orders.
* Number of customer orders.
* Category-wise product analysis.
* Product pricing segmentation.
* Customer and order relationships.
* Order status summary.
* Sales analysis using aggregate functions.

---

## 📖 SQL Concepts Demonstrated

* Database Design
* DDL (Data Definition Language)
* DML (Data Manipulation Language)
* DQL (Data Query Language)
* Constraints
* Aggregate Functions
* Joins
* Indexing
* Transactions
* Query Optimization

---

## 🎯 Learning Outcomes

By completing this assignment, I gained practical experience in:

* Designing relational databases
* Writing SQL queries for business scenarios
* Performing data analysis using SQL
* Working with JOIN operations
* Applying constraints and indexes
* Managing transactions using COMMIT and ROLLBACK
* Understanding ACID properties
* Organizing and documenting SQL projects on GitHub

---

## 👨‍💻 Author

**Abhishek Raj**

**B.Tech – Computer Science & Engineering**

**Celebal Summer Internship 2026**

GitHub: **https://github.com/RjAbhishek185**
