# Zepto_SQL_Data_Analysis
Data Analysis by using SQL

Project Overview:

This project provides a detailed view of the product catalog and pricing structure of Zepto, a fast-growing 10-minute grocery delivery platform.
This project presents a SQL-based Exploratory Data Analysis (EDA) on a Zepto-style grocery product dataset.
The analysis focuses on understanding product performance, pricing trends, stock availability, and category-level insights using PostgreSQL queries.
By performing data cleaning, transformation, and aggregation, this project simulates a real-world analytics workflow that can help e-commerce and quick-commerce platforms (like Zepto or Blinkit) make data-driven decisions about inventory and pricing strategies.

Key Features:

1. Data Cleaning & Validation:

- Removed products with invalid or zero MRP.

- Converted prices from paise to rupees for accuracy.

- Identified null and duplicate records for quality checks.

2. Exploratory Analysis:

- Counted total rows, unique categories, and stock status.

- Found duplicate product entries and analyzed availability trends.

- Explored top discount products and high-MRP out-of-stock items.

3. Analytical Insights:

- Identified top 10 best-value products by discount percentage.

- Calculated total estimated revenue per category.

- Found high-MRP, low-discount items and top 5 categories by average discount.

- Computed price-per-gram for cost efficiency analysis.

- Grouped items by weight category (Low, Medium, Bulk).

- Calculated total inventory weight per category.

4. SQL Techniques Used:

- Aggregation (SUM, AVG, COUNT, GROUP BY)

- Filtering (WHERE, HAVING)

- Data transformation using CASE, ROUND, and arithmetic operations

- Sorting and ranking with ORDER BY and LIMIT

- Data validation using conditional queries

Project Objectives:

To perform a complete Exploratory Data Analysis (EDA) using SQL that extracts meaningful insights from a grocery dataset resembling Zepto’s inventory system.
The goal is to demonstrate practical data cleaning, analysis, and business insight generation skills using only SQL — without external analytics tools — highlighting the power of SQL for end-to-end data analysis and decision-making in retail and e-commerce domains.
