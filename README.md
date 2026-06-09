# 📊 Blinkit Data Analysis Using SQL

## 📌 Project Overview

This project focuses on analyzing Blinkit's sales and outlet performance data using SQL. The analysis includes data cleaning, KPI generation, sales trends, outlet performance evaluation, and product category analysis to derive meaningful business insights.

The goal of this project is to demonstrate practical SQL skills used in real-world data analytics, including data transformation, aggregation, filtering, grouping, pivoting, and business reporting. 

---

## 🎯 Objectives

* Clean and standardize inconsistent data.
* Analyze total and average sales performance.
* Evaluate product categories and fat content trends.
* Measure outlet-wise sales performance.
* Generate business KPIs for decision-making.
* Create SQL-based analytical reports. 

---

## 🛠️ Technologies Used

* SQL Server
* SQL Queries
* Data Cleaning
* Data Aggregation
* Pivot Tables
* Business Analytics

---

## 📂 Dataset Features

The dataset contains information related to:

* Product Categories
* Item Fat Content
* Outlet Types
* Outlet Sizes
* Outlet Locations
* Outlet Establishment Year
* Total Sales
* Product Ratings
* Item Visibility

---

## 🔍 Data Cleaning Performed

Standardized inconsistent values in the `ITEM_FAT_CONTENT` column:

| Before  | After   |
| ------- | ------- |
| LF      | Low Fat |
| low fat | Low Fat |
| reg     | Regular |

This improves reporting accuracy and ensures consistent analysis across the dataset. 

---

## 📈 Key Performance Indicators (KPIs)

The project calculates:

* Total Sales
* Total Sales (Million Format)
* Average Sales
* Number of Items
* Average Rating
* Sales by Fat Content
* Sales by Item Type
* Sales by Outlet Size
* Sales by Outlet Location
* Sales by Outlet Type
* Outlet Establishment Year Analysis  

---

## 📊 Analysis Performed

### 1. Sales Analysis

* Total Sales
* Average Sales
* Sales in Specific Years
* Sales by Product Category

### 2. Product Analysis

* Sales by Item Type
* Top 5 Best-Selling Item Categories
* Fat Content Performance Analysis

### 3. Outlet Analysis

* Outlet-wise Sales Comparison
* Outlet Size Contribution
* Outlet Location Performance
* Outlet Type Performance

### 4. Customer Insights

* Average Product Ratings
* Product Visibility Analysis

### 5. Advanced SQL

* Aggregations
* GROUP BY Analysis
* CASE Statements
* Data Standardization
* PIVOT Tables
* Percentage Calculations 

---

## 📋 Sample SQL Concepts Used

```sql
SELECT SUM(TOTAL_SALES) AS TOTAL_SALES
FROM BLINKIT_DATA;
```

```sql
SELECT ITEM_TYPE,
       SUM(TOTAL_SALES) AS TOTAL_SALES
FROM BLINKIT_DATA
GROUP BY ITEM_TYPE;
```

```sql
PIVOT
(
    SUM(TOTAL_SALES)
    FOR ITEM_FAT_CONTENT IN ([LOW FAT],[REGULAR])
) AS PivotTable;
```

---

## 🚀 Skills Demonstrated

* SQL Query Writing
* Data Cleaning
* Business Intelligence
* KPI Development
* Data Aggregation
* Reporting & Analytics
* Problem Solving
* Data Visualization Preparation

---

## 👨‍💻 Author

### Pranav Saratkar

🎓 BCA Student, DCPE, Sant Gadge Baba Amravati University

📧 Email: [pranav.saratkar.work@gmail.com](mailto:pranav.saratkar.work@gmail.com)

💼 Aspiring Data Analyst | SQL | Python | Power BI | Data Analytics

---

⭐ If you found this project useful, don't forget to star the repository!
