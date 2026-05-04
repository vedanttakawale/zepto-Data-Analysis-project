Zepto Data Analysis using MySQL
-- Overview

This project analyzes a Zepto product dataset using MySQL to uncover meaningful business insights related to pricing, discounts, inventory, and product performance. The project demonstrates strong SQL skills including data cleaning, exploration, and advanced analysis.
-- Dataset Description

-- The dataset contains product-level information, including:

sku_id – Unique product ID
category – Product category
name – Product name
mrp – Maximum Retail Price
discountPercent – Discount offered (%)
discountedSellingPrice – Final selling price
availableQuantity – Inventory available
weightInGms – Product weight
outOfStock – Stock availability status
quantity – Units per package

-- Tools & Technologies
MySQL – Data analysis and querying
SQL – Data cleaning, transformation, and insights extraction

-- Data Cleaning Steps
Removed products with invalid pricing (MRP = 0)
Converted price values from paise to rupees
Checked for null values across all columns
Ensured data consistency for accurate analysis

--Key Analysis Performed
📊 Data Exploration
Total number of products
Unique product categories
Stock availability (in-stock vs out-of-stock)
Duplicate product entries

📈 Business Analysis
-Top products based on highest discounts
-High-value products that are out of stock
-Revenue estimation by category
-Low-discount premium product identification
-Categories offering highest average discounts
-Best value products based on price per gram
-Product segmentation based on weight
-Total inventory weight by category

--Project Outcome

This project highlights the ability to:

Clean and transform raw data
Perform advanced SQL analysis
Extract actionable business insights
Support decision-making using data
