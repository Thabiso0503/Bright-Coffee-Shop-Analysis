☕ Bright Coffee Shop Sales Analysis (SQL Project)
📌 Project Overview

This project analyzes historical transactional data from Bright Coffee Shop to generate actionable insights for strategic decision-making.

The primary objective is to leverage SQL and data analytics techniques to uncover sales patterns, optimize product performance, and support business growth for a new CEO.

🎯 Objectives
Identify top-performing products based on revenue
Analyze customer purchasing behavior across different time intervals
Determine peak business hours and low-activity periods
Evaluate sales trends across product categories
Provide data-driven recommendations to improve overall performance
🛠 Tools & Technologies
SQL (Databricks) – Data cleaning, transformation, and analysis
Microsoft Excel / Power BI – Data visualization and dashboards
GitHub – Version control and project documentation
🔄 Data Processing & Transformation

To prepare the dataset for analysis, the following steps were performed:

Converted raw data into a structured CSV format
Cleaned the unit_price column (handled comma-separated values such as '3,1')
Created a new metric:
total_amount = unit_price × transaction_qty
Engineered time-based features:
30-minute transaction time buckets
Hourly time segmentation
Grouped and aggregated data by product categories and time intervals
📊 Key Analysis Performed
Revenue analysis by product category
Time-based sales analysis (hourly and 30-minute intervals)
Transaction volume and quantity trends
Demand segmentation using CASE statements
Identification of peak vs low-performing periods
🔍 Key Insights
A small group of products contributes disproportionately to total revenue
Sales peak during specific periods (notably morning rush hours)
Certain time intervals show consistently low customer activity
Product demand varies significantly depending on time of day
💡 Recommendations
Increase targeted marketing during low-sales periods
Prioritize inventory for high-performing products
Introduce promotions (discounts/bundles) for underperforming items
Align staffing levels with peak business hours to improve efficiency
🚀 Project Impact

This analysis provides actionable insights that can help:

Improve revenue generation
Optimize inventory management
Enhance customer engagement strategies
Support data-driven decision-making
