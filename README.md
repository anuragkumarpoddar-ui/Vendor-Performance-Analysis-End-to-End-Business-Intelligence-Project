# 📊 Vendor Performance Analysis | End-to-End Business Intelligence Project
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)

## 📌 Project Overview

Effective inventory and vendor management are essential for maintaining profitability in the retail and wholesale industry. Poor pricing strategies, slow-moving inventory, and excessive dependency on a few suppliers can significantly affect business performance.

This project analyzes vendor performance, inventory efficiency, and profitability using Python, SQL, and Power BI to generate actionable business insights and strategic recommendations.

---

## 🎯 Business Objectives

The analysis aims to:

✔ Identify underperforming brands requiring pricing or promotional adjustments.

✔ Determine the vendors contributing most to sales and gross profit.

✔ Analyze the impact of bulk purchasing on procurement costs.

✔ Evaluate inventory turnover and identify slow-moving products.

✔ Compare profitability patterns between high-performing and low-performing vendors.

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* SQLite
* SQLAlchemy
* Matplotlib
* Seaborn
* Power BI
* Statistical Analysis
* Jupyter Notebook

---

## 📂 Dataset

The project uses transactional datasets containing information about:

* Purchases
* Sales
* Vendor invoices
* Freight costs
* Inventory
* Product and brand details

---

## ⚙️ Project Workflow

### 1️⃣ Data Ingestion

Built an automated ETL pipeline that:

* Reads multiple CSV files
* Loads them into SQLite database tables
* Creates execution logs
* Enables reproducible analysis

```python
python ingestion.py
```

---

### 2️⃣ Data Cleaning & Preprocessing

Removed inconsistent records:

* Gross Profit ≤ 0
* Profit Margin ≤ 0
* Total Sales Quantity = 0

Handled:

* Missing values
* Outliers
* Data type conversions
* Feature engineering

---

### 3️⃣ Exploratory Data Analysis

Performed:

* Summary statistics
* Distribution analysis
* Correlation analysis
* Outlier detection
* Inventory trend analysis

---

## 📈 Key Business Insights

### 🔹 Vendor Dependency

The top 10 vendors account for approximately 66% of total purchases, indicating a high dependency on a limited number of suppliers.

---

### 🔹 Bulk Purchasing Advantage

Large purchase orders reduce unit costs by approximately 72%, demonstrating significant economies of scale.

---

### 🔹 Inventory Inefficiency

Unsold inventory capital exceeds $2.71M, leading to higher holding costs and reduced cash flow efficiency.

---

### 🔹 Hidden Growth Opportunities

198 brands exhibit low sales volumes but maintain high profit margins, presenting opportunities for targeted marketing and pricing optimization.

---

### 🔹 Profitability Differences

Statistical testing confirmed significant differences between the profitability models of high-performing and low-performing vendors.

---

## 📊 Dashboard Features

The Power BI dashboard provides:

* Vendor Performance Overview
* Sales and Profit Analysis
* Inventory Turnover Metrics
* Brand Performance Analysis
* Purchase Cost Analysis
* Profit Margin Comparison
* Interactive Filters and Drilldowns

---

## 📷 Dashboard Preview

<img width="1217" height="731" alt="Vendor Performance Analysis Dashboard" src="https://github.com/user-attachments/assets/ca8ba53a-aaa8-4059-8109-9369af110212" />




## 💡 Business Recommendations

* Revisit pricing strategies for high-margin, low-sales brands.
* Diversify vendor partnerships to reduce supply chain risk.
* Utilize bulk purchasing to lower procurement costs.
* Optimize slow-moving inventory and reduce holding costs.
* Strengthen marketing strategies for underperforming vendors.

---

## 📈 Business Impact

This analysis helps organizations:

✔ Improve profitability.

✔ Reduce inventory costs.

✔ Enhance vendor management.

✔ Minimize supply chain risks.

✔ Support data-driven decision-making.

---

## 🚀 Future Improvements

* Demand forecasting using Machine Learning.
* Inventory optimization models.
* Vendor risk scoring system.
* Automated ETL pipelines using Airflow.
* Real-time dashboard integration.

---

## 👨‍💻 Author

**Anurag Kumar Poddar**

Data Analyst | Bardaha Criholic Private Limited

| Python | SQL | Power BI | Data Visualization

📧 Email: anuragkumarpoddar@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/anurag-kumar-poddar-51239596/









- Special thanks to Ayushi Mishra for her valuable guidance and support in this project. While her assistance helped me throughout the learning process, the project was independently completed by me.

