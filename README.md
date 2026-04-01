# 📊 Food Price Analysis in Nigeria

## 📌 Project Overview
This project analyzes food price dynamics in Nigeria using a combination of SQL and Python. The objective is to understand how food prices vary across commodities, regions, and market structures, and to derive insights relevant to food security and policy.

---

## 🎯 Objectives
- Analyze price variation across major food commodities  
- Examine differences in food prices across states and regions  
- Compare prices across market structures (urban vs rural, retail vs farmgate)  
- Identify trends in food prices over time  

---

## 🗂️ Dataset Description
The dataset contains food price observations across Nigeria, including:

- Date  
- State and Local Government Area (LGA)  
- Sector (Urban/Rural)  
- Outlet Type  
- Food Item  
- Price Category (Retail/Farmgate)  
- Unit Price (₦)  

---

## ⚙️ Tools & Technologies
- Python (Pandas, Matplotlib)  
- SQL (SQLite)  
- Jupyter Notebook  

---

## 🗄️ SQL Workflow
The dataset was stored in a SQLite database to enable structured querying and aggregation.

Key SQL operations performed:
- Aggregation of prices by food item  
- State-level price analysis  
- Sector and outlet comparisons  
- Time-series data extraction  

Example query:

```sql
SELECT food_item, AVG(uprice) AS avg_price
FROM food_prices
GROUP BY food_item
ORDER BY avg_price DESC;

