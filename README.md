<div align="center">

# ☕ Bright Coffee Shop Sales Analysis

### SQL Data Analytics Project

**Analyst:** Thabiso Nkambule

**Project:** Bright Coffee Shop Sales Analysis

**Tools:** SQL • Databricks SQL • Power BI • Excel

</div>

<div align="center">

![SQL](https://img.shields.io/badge/SQL-Database-blue?style=for-the-badge&logo=mysql)
![Databricks](https://img.shields.io/badge/Databricks-SQL-red?style=for-the-badge&logo=databricks)
![PowerBI](https://img.shields.io/badge/PowerBI-Visualization-yellow?style=for-the-badge&logo=powerbi)
![Excel](https://img.shields.io/badge/Microsoft-Excel-green?style=for-the-badge&logo=microsoft-excel)
![GitHub](https://img.shields.io/badge/GitHub-Version_Control-black?style=for-the-badge&logo=github)

</div>

---

# 📂 Project Structure

```
BrightCoffeeShop_SQL_Project
│
├── Dataset
│   └── coffee_shop_sales.csv
│
├── SQL Scripts
│   ├── Data_Cleaning.sql
│   ├── Feature_Engineering.sql
│   ├── Sales_Analysis.sql
│   └── Business_Insights.sql
│
├── Dashboard
│   ├── PowerBI.pbix
│   └── Dashboard_Screenshots
│
├── README.md
└── Report.pdf
```

---

# 📌 Project Overview

This project analyzes historical transactional data from **Bright Coffee Shop** to generate actionable business insights for business decision-makers.

The analysis focuses on identifying revenue drivers, customer purchasing patterns, peak business hours, and opportunities to improve profitability using SQL and data analytics techniques.

---

# 🎯 Objectives

- Identify the highest revenue-generating products
- Analyze customer purchasing behaviour
- Discover peak business hours
- Evaluate sales performance over time
- Generate business recommendations using data

---

# 🛠 Tools & Technologies

| Tool | Purpose |
|-------|----------|
| SQL | Data Cleaning & Analysis |
| Databricks SQL | Query Execution |
| Power BI | Dashboard Creation |
| Microsoft Excel | Data Exploration |
| GitHub | Documentation & Version Control |

---

# 🔄 Data Cleaning & Transformation

The raw transactional dataset required preprocessing before analysis.

### Tasks Performed

- Converted raw data into CSV format
- Cleaned inconsistent values in **unit_price**
- Removed formatting issues caused by commas
- Corrected data types
- Created calculated columns

### Calculated Field

```sql
total_amount = unit_price * transaction_qty
```

---

# ⚙️ Feature Engineering

Additional business metrics were created to improve analysis.

✔ Created 30-minute transaction intervals

✔ Extracted hourly timestamps

✔ Generated revenue metrics

✔ Categorized sales periods

✔ Grouped products into categories

---

# 📊 SQL Analysis Performed

The project includes analysis such as:

- Revenue by product category
- Total sales
- Number of transactions
- Quantity sold
- Hourly sales trends
- 30-minute interval analysis
- Peak shopping periods
- Low-performing products
- Demand segmentation using CASE statements

---

# 📈 Key Insights

✔ Coffee and beverage products generated the highest revenue.

✔ Sales peaked during morning hours, indicating commuter demand.

✔ Certain afternoon periods experienced significantly lower customer activity.

✔ Some products consistently underperformed despite high availability.

✔ Revenue distribution varied considerably across different product categories.

---

# 💡 Business Recommendations

- Increase promotions during low-sales periods.
- Improve inventory planning for high-demand products.
- Bundle underperforming items with popular products.
- Schedule more staff during peak hours.
- Introduce targeted promotions for slow-moving products.

---

# 🚀 Project Impact

This project demonstrates how SQL can be used to transform raw transactional data into actionable business intelligence.

The insights produced can help management:

- Increase revenue
- Improve inventory planning
- Optimize staffing schedules
- Enhance customer experience
- Support data-driven decision making

---

# 📷 Dashboard Preview

> Add your dashboard screenshots here.

```
images/dashboard1.png
images/dashboard2.png
```

Example:

```markdown
<p align="center">
<img src="images/dashboard1.png" width="900">
</p>
```

---

# 📚 Skills Demonstrated

- SQL Queries
- Data Cleaning
- Data Transformation
- Feature Engineering
- Aggregate Functions
- CASE Statements
- Date & Time Functions
- Business Intelligence
- Data Visualization
- Analytical Thinking

---

# 👨‍💻 Author

**Thabiso Nkambule**

Final Year BSc Computer Science Student

Walter Sisulu University

- GitHub: https://github.com/Thabiso0503
- LinkedIn: *(Add your LinkedIn profile)*

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

</div>


