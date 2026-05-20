# Digital Banking SQL Project

## Overview

This project demonstrates a Digital Banking Management System built using MySQL Workbench. The system digitizes traditional banking operations by managing customer accounts, transactions, cards, and loans through structured database design and SQL queries.

The project focuses on:

* Database schema design
* EER modeling
* SQL queries and joins
* Subqueries and window functions
* Banking analytics and reporting

It simulates real-world banking operations and showcases how SQL can support efficient decision-making in digital banking environments.

---

# Abstract

Digital banking digitizes all traditional banking activities, allowing customers to manage accounts, transfer funds, pay bills, and invest using online platforms and mobile applications without visiting physical branches.

This project is designed using MySQL Workbench and includes:

* Customer details
* Accounts
* Transactions
* Loans
* Cards

Advanced SQL concepts such as joins, subqueries, views, and window functions are used to generate business insights. A snowflake schema is implemented to support scalable analytics and reporting.

The project demonstrates practical SQL implementation for modern banking systems.

---

# Technologies Used

* MySQL Workbench
* SQL
* Database Modeling
* Snowflake Schema

---

# Database Design

## EER Diagram

The project includes an Extended Entity Relationship (EER) diagram representing relationships between:

* Customers
* Accounts
* Transactions
* Loans
* Cards

---

# Database Tables

## 1. Customers Table

Stores customer information and profile details.

### Key Attributes

* Customer ID
* Customer Name
* Contact Information
* Address
* Customer Type

---

## 2. Accounts Table

Maintains account-related information.

### Key Attributes

* Account ID
* Customer ID
* Account Type
* Balance
* Open Date

---

## 3. Transactions Table

Stores customer transaction history.

### Key Attributes

* Transaction ID
* Account ID
* Transaction Type
* Transaction Amount
* Transaction Date

---

## 4. Loans Table

Contains loan-related information.

### Key Attributes

* Loan ID
* Customer ID
* Loan Amount
* Interest Rate
* Loan Status

---

## 5. Cards Table

Stores debit and credit card details.

### Key Attributes

* Card ID
* Customer ID
* Card Type
* Card Status
* Expiry Date

---

# SQL Operations and Analysis

## 1. Customer Base Calculation

### Objective

Identify the total customer base for marketing analysis.

### SQL Concept Used

* `SELECT * FROM customers`

### Business Benefit

Helps the bank understand customer growth and marketing opportunities.

---

## 2. Loan Status Analysis

### Objective

Track loans pending for disbursement.

### SQL Concept Used

* `WHERE` clause
* `IN` operator

### Business Benefit

Improves monitoring of pending loan approvals.

---

## 3. Account Opening Status

### Objective

Analyze account opening activity and balances.

### SQL Concept Used

* `SELECT * FROM accounts`

### Business Benefit

Tracks account growth and account balances.

---

## 4. High Interest Loans

### Objective

Identify loans with high interest rates.

### SQL Concept Used

* `WHERE`
* Comparison operators (`>`)

### Business Benefit

Helps identify high-return lending opportunities.

---

## 5. Debit and Credit Card Status

### Objective

Track debit and credit card holders.

### SQL Concept Used

* `SELECT * FROM cards`

### Business Benefit

Supports targeted credit card marketing campaigns.

---

## 6. High Balance Accounts

### Objective

Identify accounts with large balances.

### SQL Concept Used

* `LEFT JOIN`

### Business Benefit

Helps identify High Net-Worth Individuals (HNIs) for premium banking services.

---

## 7. Loan Amount Analysis

### Objective

Analyze large loan disbursements.

### SQL Concept Used

* `LEFT JOIN`

### Business Benefit

Supports future lending and business expansion strategies.

---

## 8. Debit Card Holder Analysis

### Objective

Identify debit card holders.

### SQL Concept Used

* `LEFT JOIN`

### Business Benefit

Useful for future customer engagement and analytics.

---

## 9. Transaction Status Analysis

### Objective

Track cash-based transactions.

### SQL Concept Used

* `LEFT JOIN`

### Business Benefit

Encourages digital banking adoption over cash transactions.

---

## 10. Loan Sanction Status

### Objective

Analyze loan sanction and disbursement status.

### SQL Concept Used

* `LEFT JOIN`

### Business Benefit

Improves conversion of sanctioned loans into disbursed loans.

---

## 11. UPI Transaction Analysis

### Objective

Analyze UPI and cash transaction trends.

### SQL Concept Used

* Window Functions
* `SUM()` with `PARTITION BY`

### Business Benefit

Supports digital payment adoption initiatives.

---

## 12. High Balance Ranking

### Objective

Rank accounts by balance.

### SQL Concept Used

* Window Functions
* `RANK()` with `PARTITION BY`

### Business Benefit

Identifies top-performing accounts.

---

## 13. Average Balance Analysis

### Objective

Find accounts maintaining balances higher than average.

### SQL Concept Used

* Multi-row subquery

### Business Benefit

Identifies valuable banking customers.

---

## 14. Disbursement Analysis

### Objective

Analyze loan disbursement amounts.

### SQL Concept Used

* Scalar (single-row) subquery

### Business Benefit

Tracks loan disbursement performance.

---

## 15. Average Disbursement Comparison

### Objective

Identify customers receiving higher-than-average disbursements.

### SQL Concept Used

* Correlated subquery

### Business Benefit

Supports strategic loan analysis.

---

# Key SQL Concepts Covered

* SELECT Queries
* WHERE Clause
* JOIN Operations
* LEFT JOIN
* Subqueries
* Correlated Subqueries
* Scalar Subqueries
* Window Functions
* RANK()
* SUM() OVER(PARTITION BY)
* Snowflake Schema Design

---

# Business Insights Generated

The project helps banking organizations:

* Improve digital banking adoption
* Monitor customer transactions
* Analyze customer balances
* Improve loan management
* Identify high-value customers
* Enhance marketing strategies
* Increase operational efficiency

---

# Conclusion

This project highlights the importance of SQL in modern banking systems.

Advanced SQL concepts such as joins, subqueries, and window functions are used to:

* Improve loan disbursement analysis
* Promote digital transactions
* Enhance reporting capabilities
* Support data-driven decision-making

Digital banking offers:

* 24/7 banking access
* Improved convenience
* Faster transactions
* Enhanced security
* Reduced operational costs

The project demonstrates how a well-designed relational database system can significantly improve efficiency and customer experience in the banking industry.

---

# Future Enhancements

* Add real-time transaction monitoring
* Implement fraud detection
* Integrate dashboards and visual analytics
* Add customer authentication systems
* Build API-based banking services
* Enable mobile banking integration

---

# Author

**Bhushan Sakhalkar**
