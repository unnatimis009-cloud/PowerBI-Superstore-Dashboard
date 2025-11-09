# PowerBI-Superstore-Dashboard
Power BI project analyzing Superstore sales and profit data using Power Query, DAX, and interactive dashboard visuals.

This project showcases a complete end-to-end data analytics workflow using **Microsoft Power BI**.  
The goal was to transform the Superstore dataset into a visually engaging and insight-driven **business intelligence dashboard**.

 📊 Key Features
- Built interactive visualizations to explore **Sales**, **Profit**, and **Regional Performance**
- Cleaned and transformed the dataset using **Power Query**
- Created dynamic **DAX measures** for KPIs like:
  - Total Sales
  - Total Profit
  - Profit Margin %
  - Total Orders
- Designed a clean and professional dashboard with:
  - **Sales by Category**
  - **Profit by Region**
  - **Sales Trend Over Time**
  - **Top 10 Products by Sales**

 🧮 DAX Measures
```DAX
Total Sales = SUM(Superstore[Sales])
Total Profit = SUM(Superstore[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales])
Total Orders = COUNTROWS(Superstore)
