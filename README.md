# NaijaPhoneShop Sales Analysis

## Introduction
Retail businesses rely on clear visibility into sales performance to make informed decisions about stock, staffing, and growth. This project analyzes a full year of sales transactions from NaijaPhoneShop, a fictional phone and accessories retailer, to uncover patterns in revenue, customer behavior, staff performance, and product demand, presented through an interactive Power BI dashboard.

## Problem Statement
With sales happening across multiple cities, staff, and payment methods, it can be difficult to see which areas are driving revenue and which products are moving fastest. This project explores the transaction data to answer key questions: which cities and staff generate the most revenue, which payment methods are most used, and which products sell the most, in order to support better business decisions.

## Data Sourcing
The dataset is the NaijaPhoneShop Sales 2024 transaction dataset.

**Key Fields:**
- City
- Product
- Quantity
- Unit price
- Total amount
- Payment method
- Date
- Staff

## Data Transformation & Cleaning
- Used SQL to clean and prepare the raw transaction data before analysis
- Identified and fixed Null and error values in the Quantity, Unit Price, and Total Amount fields
- Standardized inconsistent entries across city, product, and payment method fields

## Analytics and Measures
Built DAX measures and visuals in Power BI, covering:
- Total revenue, total customers, total transactions, and average order value
- Revenue by month and by city
- Revenue by staff member
- Revenue by payment method
- Total quantity sold and total products
- Quantity sold by month and by product

## Dashboard & Visuals
Designed a two-page interactive Power BI report:

**Page 1 — Sales Analysis**
- KPI cards: Total Revenue, Total Customers, Total Transactions, Average Order
- Revenue by Month (line chart)
- Revenue by City (pie chart)
- Revenue by Staff (bar chart)
- Revenue by Payment (bar chart)
- Slicers: City, Payment, Month, Product

**Page 2 — Sales Performance**
- KPI cards: Quantity Sold, Total Product
- Quantity Sold by Month (line chart)
- Product by Amount (table)
- Transaction by Staff (bar chart)
- Quantity Sold by Product (bar chart)

![NaijaPhone Sales Analysis](naijaphone-sales-dashboard.png)
![NaijaPhone Sales Performance](naijaphone-sales-dashboard-2.png)

## Insight and Findings
- Total revenue for the year reached 13M, across 918 transactions from 762 customers, with an average order value of 13.94K.
- Lagos and Ibadan were the top revenue-generating cities, together accounting for a large share of total sales.
- Bank transfer and USSD were the most used payment methods.
- The Hdmi Cable and Laptop Bag were among the top products by quantity sold, while higher-value items like Laptop Bag and Bluetooth Speaker led in revenue.

## Recommendations
- Focus marketing and stock efforts on top-performing cities and products to maximize revenue.
- Encourage wider use of digital payment methods (bank transfer, USSD) given their popularity.
- Review staff performance data to identify training or support opportunities for lower-performing staff.

## Conclusion
This analysis shows how transaction-level sales data can be transformed into clear, actionable insights on revenue drivers, customer behavior, and product performance, supporting smarter business decisions for NaijaPhoneShop.
