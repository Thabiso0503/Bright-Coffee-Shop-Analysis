# ☕ Bright Coffee Shop Sales Analysis (SQL Project)

## 📌 Project Overview
This project analyzes historical transactional data from **Bright Coffee Shop** to generate actionable business insights for a new CEO.  

The goal is to use SQL and data analytics techniques to understand sales performance, identify trends, and provide recommendations to improve revenue and product performance.

---

## 🎯 Objectives
- Identify which products generate the most revenue  
- Analyze peak business hours and customer activity  
- Examine sales trends across products and time intervals  
- Provide data-driven recommendations to improve performance  

---

## 🛠 Tools & Technologies
- **SQL** (Data Cleaning & Analysis)  
- **Databricks / SQL Environment**  
- **Microsoft Excel / Power BI** (Visualization)  
- **GitHub** (Project documentation & version control)  

---

## 🔄 Data Processing & Transformation
The dataset required cleaning and transformation before analysis:

- Converted raw data into structured format (CSV)  
- Cleaned `unit_price` column (handled comma-separated values like `'3,1'`)  
- Created calculated field:  
  - `total_amount = unit_price * transaction_qty`  

### ⏱ Feature Engineering
- Created **30-minute transaction time buckets**  
- Performed **hourly analysis using timestamps**  
- Grouped data by **product types and time intervals**  

---

## 📊 Key Analysis Performed
- Revenue analysis by product type  
- Time-based sales analysis (hourly & 30-minute intervals)  
- Transaction volume and quantity analysis  
- Demand segmentation using `CASE` statements  
- Identification of peak and low-performing periods  

---

## 🔍 Key Insights
- Certain product categories generate significantly higher revenue than others  
- Sales peak during specific time intervals (e.g., morning rush hours)  
- Some time periods show low customer activity, indicating opportunities for promotions  
- Sales trends vary across different products and time buckets  

---

## 💡 Recommendations
- Increase marketing during low-sales periods  
- Focus on stocking high-performing products  
- Promote underperforming items through discounts or bundles  
- Align staffing and operations with peak hours  

---

## 🚀 Project Impact
This project demonstrates how data analytics can be used to:
- Improve revenue generation  
- Optimize inventory management  
- Enhance customer engagement strategies  
- Support data-driven decision-making  

---


