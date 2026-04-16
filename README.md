# 📊 AdventureWorks Sales Analytics | End-to-End BI Project


## 🧠 Executive Summary

This project demonstrates a complete end-to-end data analytics pipeline using the AdventureWorks dataset.

It covers the full workflow from data understanding → cleaning → modeling → DAX → dashboard development.

The goal is to transform raw data into actionable insights that support business decision-making.

---

## 🔄 Data Analytics Pipeline

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Data Modeling (Star Schema)
5. DAX Calculations
6. Dashboard Development
7. Insights & Recommendations

---

## 📂 Dataset

* AdventureWorks Sales Dataset
* Includes Sales, Products, Customers, Dates, Territories

---

## 🔍 Data Understanding

* Identified Fact & Dimension tables
* Defined key business metrics (Sales, Profit, Orders)
* Analyzed relationships between entities

---

## 🧹 Data Cleaning

```
- Removed duplicates
- Handled missing values
- Fixed data types
- Standardized column names
- Removed unnecessary columns
```

---

## 🧱 Data Modeling

* Implemented Star Schema

Fact Table:

* Sales

Dimension Tables:

* Product
* Customer
* Date
* Territory

<div style="display:flex; flex-wrap: wrap; gap: 10px;">
    <img src="https://github.com/AbdoElsayed2001/AdventureWorks-Sales-Analytics-End-to-End-BI-Project/blob/main/assets/5.PNG" width="400" alt="Screenshot 1"/>
</div>

---

## 🧮 DAX Measures

```DAX
Total Sales = SUM(Sales[SalesAmount])

Total Profit = SUM(Sales[Profit])

Total Orders = COUNT(Sales[OrderID])

Profit Margin = DIVIDE([Total Profit], [Total Sales])

Sales Growth =
VAR Prev = CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date[Date]))
RETURN [Total Sales] - Prev
```

---

## 📊 Dashboard Overview

<div style="display:flex; flex-wrap: wrap; gap: 10px;">
    <img src="https://github.com/AbdoElsayed2001/AdventureWorks-Sales-Analytics-End-to-End-BI-Project/blob/main/assets/15.PNG" width="600" alt="Screenshot 1"/>
</div>

---

## 📊 KPIs

* Total Sales
* Total Profit
* Profit Margin
* Total Orders
* Year-to-Date Sales
* Sales Growth

---

## ⚙️ Dashboard Features

* KPI Cards
* Time-series analysis
* Regional performance
* Product insights
* Interactive filters

---

## 💡 Key Insights

* High revenue does not always mean high profit
* Some regions outperform others
* Sales show seasonal patterns
* Certain products have higher margins

---

## 🚀 Business Impact

* Identify growth opportunities
* Improve product strategy
* Monitor performance
* Enable faster decisions

---

## 🛠️ Tools & Technologies

* Power BI
* DAX
* Data Modeling
* Data Cleaning
* Business Intelligence

---

## 🎯 Key Takeaway

This project demonstrates building a full data pipeline and delivering business-ready insights.

---

## ⭐ Support

If you like this project, give it a star ⭐
