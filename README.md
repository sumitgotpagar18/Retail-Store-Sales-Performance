# Retail-Store-Sales-Performance

## Introduction
The retail chain wants to understand its sales performance across regions, products, and seasons. The data contains point-of-sale records, including store location, product category, sales amount, discount and stock level.

The business goals are:
- Identify top-performing regions and stores.
- Discover which product categories have the highest margins.
- Analyze sales trends across months and seasons.
- Detect stockout issues.
- Understand discount impact on sales volume.
- Rank the top 10 products driving revenue.

## Data Exploration:
### Data Source: 
Retail point-of-sale records provided by the chain.
### Features: 
Date, Store_ID, Region, Product Category, Product Name, Unit Sold, Unit Price, Discount, Stock Remaining
### Initial Checks: 
Missing values, duplicates, outliers were handled.

## Methods: 
- Grouping and Aggregation for sales by region, store and category.
- Trend Analysis using monthly/seasonal revenue.
- Correlation Analysis between discounts and sales volume.
- Ranking products by revenue contribution.
- Stockout Analysis by counting zero-stock events per store.

## Modelling and Results:
Q1.Top Region and stores
- Region with highest sales: East, 
- Store with highest revenue: Store S020

Q2.Product category with highest profit margin.
- Electronics showed the highest profit margin.

Q3.Sales Trends by Month/Season
- Peak sales in December (holiday season)
- Summer showed moderate sales, while Autumn was lowest.

Q4.Frequent Stockouts
- Store S017 had the most frequent stockout.

Q5.Discounts vs Sales Volume
- Correlation between discount and sales volume= -0.14(negative relationship)

Q6.Top 10 Products by Sales
- Smartphone, Toaster, Tennis Racket, Running Shoes, Lipstick, Vacuum, Microwave, Laptop, Shoes, Football

## Conclusion:
- North region and Store S020 are the top performers.
- Electronics category are the most profitable.
- Holiday season drives peak sales, requiring better stock management.
- Stockouts must be reduced, especially at S112 and S109.
- Discounts boost sales volume significantly, but should be optimized to maintain margins.
- The top 10 products account for a major share of revenue and should be prioritized in promotion and inventory planning.

