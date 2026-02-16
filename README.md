*Overview* :

This project performs structured data exploration and business analysis on a retail product dataset modeled after Zepto’s inventory system. The goal is to demonstrate practical SQL skills including data cleaning, aggregation, conditional logic, and revenue analysis.
The analysis focuses on identifying pricing patterns, discount strategies, stock availability, and revenue opportunities across product categories.

*Database Schema* :

* The project uses a single table: zepto
  
sku_id -
Unique product identifier (Primary Key);
   category-
Product category;
   name-
Product name;
   mrp-
Maximum Retail Price;
   discountpercent-
Discount percentage;
   availablequantity-
Available stock quantity;
   discountedsellingprice-
Final selling price after discount;
   weightingram-
Product weight (grams);
   outofstock-
Stock availability status;
   quantity-
Total listed quantity

*Project Workflow* :

1. Data Exploration
* Total record count
* Sample data preview
* NULL value detection
* Unique category extraction
* In-stock vs Out-of-stock comparison
* Duplicate product detection
2. Data Cleaning
* Removed records with invalid pricing (MRP = 0)
* Converted price values from paise to rupees
* Validated corrected price structure
3. Business Analysis Queries
* Top 10 products with highest discount percentage
* High-value out-of-stock products (MRP > ₹300)
* Estimated revenue per category
* Premium products with low discounts
* Top 5 categories by average discount
* Best-value products (price per gram analysis)
* Weight-based product classification (Low / Medium / Bulk)
* Total inventory weight per category
* 
*Key SQL Concepts Used* :

* SELECT, WHERE, ORDER BY
* GROUP BY, HAVING
* CASE statements
* UPDATE, DELETE
* Aggregate functions (SUM, AVG, COUNT, ROUND)
  
*Tools & Environment* :

PostgreSQL / MySQL
SQL Editor (pgAdmin / MySQL Workbench)

*Outcome* :

This project showcases how SQL can be used to transform raw retail inventory data into meaningful business insights. It demonstrates strong fundamentals in data cleaning, aggregation, and analytical querying, making it suitable for entry-level data analyst or SQL developer portfolios.
