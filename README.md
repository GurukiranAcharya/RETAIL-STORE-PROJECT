#Retail Store Sales Dashboard – Power BI Project

This is a professional, interactive **Retail Sales Dashboard** created using **Power BI** to analyze and visualize the performance of a fictional retail store. The dashboard is designed to help business stakeholders track key sales metrics, monitor trends, and gain insights into product and regional performance.
Project Overview

As a **Data Analyst Fresher**, I built this project to demonstrate my ability to:
- Import and clean data using **Power Query**
- Model relationships between tables
- Write **DAX** measures for dynamic KPIs
- Build an insightful, user-friendly dashboard

Dashboard Features

✅Key KPIs:
- **Total Sales**
- **Total Orders**
- **Unique Customers**
- **Average Order Value**

📈Visualizations:
- Sales Trend by Month
- Sales by Product Category
- Top 5 Products by Revenue
- Top 5 Customers
- Sales by Region (Map View)
- Filters for Region, Category, and Date Range

⚙️DAX Measures:
```DAX
Total Sales = SUM(Sales[Sales Amount])
Total Orders = COUNT(Sales[Order ID])
Unique Customers = DISTINCTCOUNT(Sales[Customer ID])
Average Order Value = [Total Sales] / [Total Orders]
