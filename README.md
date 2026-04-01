# Food Price Analysis in Nigeria

## Project Overview
This project analyzes food price dynamics in Nigeria using a combination of SQL and Python. The objective is to understand how food prices vary across commodities, regions, and market structures, and to derive insights relevant to food security and policy.

---

## Objectives
- Analyze price variation across major food commodities  
- Examine differences in food prices across states and regions  
- Compare prices across market structures (urban vs rural, retail vs farmgate)  
- Identify trends in food prices over time

---

## Tools & Technologies
- Python (Pandas, Matplotlib)  
- SQL (SQLite)  
- Jupyter Notebook  

---

## SQL Workflow
The dataset was stored in a SQLite database to enable structured querying and aggregation.

Key SQL operations performed:
- Aggregation of prices by food item  
- State-level price analysis  
- Sector and outlet comparisons  
- Time-series data extraction  

## Time-Series Analysis
<img width="989" height="490" alt="Average Food Price Trend Over Time" src="https://github.com/user-attachments/assets/bbefd570-f98b-4cb2-84d8-2dda2b22804e" />

The time-series analysis shows how average food prices evolved over the observed period. Prices exhibit noticeable fluctuations, with an initial spike followed by relative stabilization. This pattern suggests the presence of short-term market shocks possibly due to supply disruptions, seasonal effects, or inflationary pressures—followed by gradual market adjustment.

Overall, the trend highlights the dynamic nature of food prices in Nigeria and the importance of continuous monitoring for effective policy response.

## Commodity Price Analysis
<img width="989" height="490" alt="Average Food Pirces by Commodity" src="https://github.com/user-attachments/assets/91f1c16f-60d2-4671-8022-0a0c233e0ea7" />

The comparison of average prices across food commodities reveals clear disparities. Imported rice emerges as the most expensive commodity, followed by beans and local rice, reflecting strong consumer demand and potential supply constraints.

In contrast, staples such as maize, sorghum, and garri are relatively more affordable, indicating their role as key food sources for lower-income households. These differences highlight the structure of food consumption and the economic significance of staple crops in Nigeria.

## Regional Price Comparison
<img width="790" height="490" alt="Average food prices by region in Nigeria" src="https://github.com/user-attachments/assets/965d57c3-e5db-4d18-8529-37aab6d98156" />

Food prices vary significantly across regions in Nigeria. Southern regions tend to exhibit higher average prices compared to northern regions, likely due to higher urbanization, transportation costs, and demand pressures.

Conversely, northern regions—being major agricultural production zones generally show lower prices. This regional disparity points to inefficiencies in market integration and the need for improved distribution systems to enhance price stability nationwide.

## Market Structure Analysis (Outlet Type)
<img width="989" height="590" alt="Average food prices by outlet type" src="https://github.com/user-attachments/assets/b8adaf24-8e14-4220-bfa7-00c6de077a84" />

Price differences across outlet types reveal important insights into Nigeria’s food value chain. Supermarkets and formal retail outlets tend to have higher prices, reflecting additional costs such as storage, packaging, and overhead expenses.

On the other hand, food purchased directly from farmers or in open markets is relatively cheaper, indicating shorter supply chains and lower transaction costs. This highlights the role of intermediaries and distribution channels in shaping food prices.

## Key Takeaway

This project demonstrates how data-driven analysis can support understanding of food price dynamics in Nigeria, with implications for policy and food security.
