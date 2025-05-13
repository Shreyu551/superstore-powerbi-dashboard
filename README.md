# 📊 Super Store Sales Dashboard (Power BI Project)
## 🔍 Overview
This Power BI dashboard project analyzes the Super Store Sales dataset with the objective of deriving meaningful business insights from historical sales data. It provides a visually rich and interactive interface for monitoring sales performance, profit, orders, and shipping efficiency across different dimensions.

## 🎯 Objectives
  * Visualize key metrics: Sales, Profit, Orders, and Shipping Days.
  * Understand sales performance across various categories, segments, regions, and payment modes.
  * Analyze monthly trends in sales and profit over time.
  * Identify top-performing subcategories, states, and shipping methods.

## ❓ Key Questions Considered
1 -> Before building the dashboard, I focused on answering these business questions:

2 -> Which region and state have the highest sales and profit?

3 -> What are the monthly trends in sales and profit?

4 -> Which product categories and subcategories contribute the most to revenue?

5 -> How do different payment modes, segments, and ship modes impact performance?

6 -> How quickly are orders being delivered?

## 📁 Dataset Details
Source: Sample Superstore dataset (- <a href="https://github.com/Shreyu551/superstore-powerbi-dashboard/blob/main/SuperStore_Sales_Dataset.csv">Dataset</a>)

Format: Excel / CSV

Columns Used:
  * Order Date, Region, Segment, Category, SubCategory
  * Sales, Profit, Quantity, Ship Mode
  * Payment Mode, State, Customer Info

## 🧰 Tools & Skills Used
 * Power BI Desktop
 * Power Query (for data cleaning & transformation)
 * DAX (for calculated measures like total profit, orders)
 * Drill-through & Tooltips
 * Visualizations: Donut Charts, Line Graphs, Bar Charts, Map Visuals, KPIs

## 🛠️ Process Followed
 * Data Import – Loaded the dataset into Power BI from Excel.
 * Data Cleaning – Handled missing values, removed duplicates, and converted data types.
 * Data Modeling – Created relationships where needed and optimized the model for reporting.
 * DAX Measures – Defined KPIs like Total Sales, Total Profit, Order Count, Avg Ship Days.
 * Dashboard Design – Added intuitive layout, slicers, and grouped visuals logically:
 * KPIs at the top: Sales, Profit, Orders, Ship Days.
 * Filters: Region selector to switch views dynamically.
 * Breakdowns: Payment Mode, Region, Segment, Category, Ship Mode, SubCategory.
 * Maps and Trends: Monthly trends and state-wise profit mapping.
 * User Interactivity – Enabled slicers and drill-down functionality.

## 🔑 Key Insights
 * The East region had 100% of current filtered sales (based on filter selection).
 * Cards were the most popular payment mode.
 * Corporate Segment drove the most revenue.
 * Office Supplies and Phones were top revenue-generating categories/subcategories.
 * Standard Class shipping was the most frequently used.
 * There is a visible seasonal trend with a sales peak around November and December.
