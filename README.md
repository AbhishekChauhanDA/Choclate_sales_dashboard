# Choclate_sales_dashboard
GitHub README preview and copy tool for the Chocolate Sales Power BI Dashboard project
Chocolate Sales Dashboard — Power BI
Interactive sales analytics dashboard built in Microsoft Power BI Desktop

Power BI
DAX
Data Modelling
Time Intelligence
KPI Dashboard
5 Tables
5 Measures
7 Visuals
Visuals on the dashboard
KPI Cards (x4)
total profit
Total sale
Total Customers
Total Products
Headline KPIs
Line Chart
mom_profit %
Date Hierarchy
(Year / Month)
Trend
Clustered Column
customers.age group
Total sale
Audience
Treemap
products.category
products.product_name
Total sale
Products
Slicers (x3)
stores.country
stores.city
stores.store_type
Filters
Data model — 5 tables
measures table
total profit
Total sale
Total Customers
Total Products
mom_profit %
calendar
date
→ Year
→ Month
customers
age group
products
product_name
category
stores
country
city
store_type
DAX measures
Total Sale
Sum of all sales revenue across products and stores
total profit
Net profit after costs — the bottom-line performance metric
Total Customers
Count of distinct customers who have made purchases
Total Products
Count of distinct products sold or listed in the catalogue
mom_profit %
Month-over-Month profit % change using calendar time intelligence
Ready-to-copy README.md
Chocolate Sales Dashboard — Power BI

Overview

An interactive single-page sales analytics dashboard built in Microsoft Power BI Desktop. The dashboard gives sales managers a complete commercial picture — headline KPIs, month-over-month profit trends, customer age segmentation, and product revenue breakdown — all filterable by country, city, and store type.

File

choclate_sales_dashboard.pbix

Dashboard visuals

| Visual | Type | Fields |
|--------|------|--------|
| Headline KPIs | KPI Card (x4) | Total Sale, Total Profit, Total Customers, Total Products |
| Profit trend | Line Chart | mom_profit %, Date Hierarchy (Year / Month) |
| Sales by age group | Clustered Column | customers[age group], Total sale |
| Revenue by product | Treemap | products[category], products[product_name], Total sale |
| Country filter | Slicer | stores[country] |
| City filter | Slicer | stores[city] |
| Store type filter | Slicer | stores[store_type] |

Data model — 5 tables

| Table | Key columns | Role |
|-------|-------------|------|
| measures table | All DAX measures | Central calculation layer |
| calendar | date → Year, Month | Time intelligence & date hierarchy |
| customers | age group | Customer demographic dimension |
| products | product_name, category | Product & category dimension |
| stores | country, city, store_type | Geographic & channel dimension |

DAX measures

- Total Sale — sum of all sales revenue
- total profit — net profit after costs
- Total Customers — distinct customer count
- Total Products — distinct product count
- mom_profit % — month-over-month profit % change

Power BI concepts used

DAX Measures Table · Star Schema · Time Intelligence · Date Hierarchy · Cross-filter Slicers · KPI Cards · Treemap · MoM % Calculation

Tools

Microsoft Power BI Desktop
