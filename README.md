 E-Commerce Sales Analysis Dashboard (Power BI)
 Overview

This project presents an interactive Power BI dashboard designed to analyze an e-commerce dataset and generate actionable business insights. The dashboard transforms raw transactional data into meaningful visualizations that support data-driven decision-making.

It focuses on key business areas such as:
Sales performance
Customer behavior
Product analysis
Regional trends
Time-based insights

 Objectives
Develop a multi-page interactive dashboard
Apply data modeling (star schema)
Create DAX measures for business KPIs
Perform time intelligence and trend analysis
Enable user interactivity through slicers and filters

Dataset Description
The dataset is based on a retail/e-commerce (Superstore-style) dataset containing transactional sales records.

Key Fields:
Order ID
Order Date
Customer ID
Segment (Consumer, Corporate, Home Office)
Product Name
Category & Sub-Category
Sales
State & Region

Data Preparation
Data cleaning and transformation were performed in Power Query:

Removed unnecessary columns
Fixed data types (Date, Numeric)
Extracted Year, Month, and Quarter
Created Month Number for proper sorting
Ensured data consistency for modeling

Data Model
A Star Schema was implemented:
Fact Table:
Fact_Orders – transactional data
Dimension Tables:
Dim_Customers
Dim_Products
Dim_Date
Dim_Location

✔ One-to-many relationships
✔ Optimized for performance and scalability

DAX Measures
Core Metrics:
Total Sales
Total Orders
Total Customers
Analytical Metrics:
Average Order Value (AOV)
Year-to-Date (YTD) Sales
Previous Year Sales
Sales Growth (%)
Advanced Metrics:
Product Ranking (RANKX)
Sales Contribution (%)
Top/Bottom Performers

Dashboard Structure

Page 1: Executive Summary
KPI Cards (Sales, Orders, Customers, AOV)
Sales Trend Line Chart
Category Comparison
Slicers (Year, Region, Category, Segment)

Page 2: Detailed Analysis
Drill-down Column Chart (Category → Product)
Matrix Table (Region vs Category)
Decomposition Tree
Scatter Plot (Sales vs Orders)
Ribbon Chart (Category ranking over time)

Page 3: Insights & Performance
Sales vs Previous Year Trend
Growth KPI (%)
Top 10 & Bottom 10 Products
Regional Performance Map

Interactivity Features
Dynamic slicers and filters
Cross-filtering across visuals
Drill-down functionality
Tooltips for additional context
Play axis (scatter plot animation)

Key Insights
Sales exhibit seasonal trends over time
A small number of products drive the majority of revenue
Customer segments behave differently in purchasing patterns
Regional performance varies significantly

Recommendations
Focus on top-performing products for revenue growth
Improve or phase out underperforming items
Target high-value customer segments
Optimize strategies in underperforming regions
Leverage seasonality for forecasting and planning

🛠️ Tools & Technologies
Power BI
DAX (Data Analysis Expressions)
Power Query
Data Modeling (Star Schema)
