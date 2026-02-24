# zepto-sql-analysis
SQL data cleaning and analysis project using Zepto product dataset
Zepto Product Data Analysis using SQL

 Overview

This project analyses a Zepto product dataset using PostgreSQL to simulate a real-world product analytics workflow. The objective was to clean raw product data, validate dataset quality, and generate business insights related to pricing, discounts, inventory availability, and category-level performance.

---

 Business Problem

E-commerce platforms manage thousands of products across multiple categories with varying pricing structures, discounts, and inventory levels.
To support pricing strategy, stock monitoring, and category performance evaluation, analysts require structured queries that can:

- Detect invalid or inconsistent pricing records
- Identify duplicate or repeated product entries
- Track stock availability across products
- Evaluate discount patterns and product value
- Estimate potential revenue contribution by category

This project builds SQL queries to address these analytical needs.

---

 Data Preparation & Cleaning

The dataset was cleaned and validated using SQL:

- Checked for NULL values across key product attributes
- Removed products with zero MRP and selling price
- Converted price values from paise into rupees
- Verified SKU uniqueness and examined duplicate product names

These steps ensured the dataset was reliable before performing analysis.

---

 Analytical Queries Implemented

SQL queries were developed to generate business-focused insights such as:

- Identifying top products based on discount percentage
- Detecting high-MRP products that are currently out of stock
- Estimating category-level revenue using selling price and available quantity
- Finding products with high price but low discount levels
- Calculating average discount percentage by category
- Computing price-per-gram metrics for product value comparison
- Classifying products into weight segments (Low, Medium, Bulk)
- Calculating total inventory weight per category

These analyses demonstrate how SQL can be used for operational monitoring and product performance evaluation.

---

 Technical Implementation

- Database created and structured using PostgreSQL
- Queries written using filtering, aggregation, CASE statements, grouping, and sorting
- Designed workflow following a typical analytics pipeline:
  1. Data exploration
  2. Data cleaning
  3. Business analysis queries

---

 Tools Used

- PostgreSQL
- SQL
- Excel dataset
- Kaggle (dataset source)

---

 Repository Contents

- SQL script containing table creation, cleaning, and analysis queries
- Documentation (this README)

---
