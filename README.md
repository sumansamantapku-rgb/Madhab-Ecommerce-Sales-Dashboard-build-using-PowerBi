🛒 Madhav E-commerce Sales Dashboard Analysis
✨ Project Overview
This repository showcases a comprehensive E-commerce Sales Analysis Dashboard created to provide Madhav Store with clear, actionable insights into their online sales performance across India. The dashboard enables stakeholders to track key performance indicators (KPIs), identify profitable customer segments, and understand regional and product-level trends.

The goal of this project was to transform raw transactional data into a visually compelling and interactive tool, supporting data-driven decision-making for business growth.

power bi service project link:
(https://app.powerbi.com/links/vOaQcPdOjb?ctid=c181540e-95e2-408b-aead-cdef017d0b5f&pbi_source=linkShare&bookmarkGuid=0babf919-ae65-4d8c-8014-4f23b8c75168)

![Alt Text](https://github.com/sumansamantapku-rgb/Madhab-Ecommerce-Sales-Dashboard-build-using-PowerBi/blob/main/Screenshot%202025-11-08%20102420.png?raw=true)

📊 Key Insights and Features
The interactive dashboard is designed around several pages and features the following core KPIs and visualizations:

1. Sales Performance Overview
Total Sales & Profit: High-level metrics for quick performance assessment.

Year-over-Year (YoY) Comparison: Track sales and profit growth/decline over time.

Profit Margin %: Monitor the efficiency and profitability of sales operations.

2. Geographical & Customer Analysis
Sales by State/Region: An interactive map visualising sales distribution and highlighting top-performing states.

Top 5 Customers: Identify and track the most valuable customers by sales amount.

3. Product & Operations Deep Dive
Sales & Profit by Category/Sub-Category: Determine the most (and least) successful product lines.

Quantity by Payment Mode: Insights into popular payment methods to optimize checkout processes.

Monthly Profit Trend: A time-series analysis to show seasonality and performance stability.


Tool,Purpose
Microsoft Power BI Desktop,"Core tool for data modeling, DAX calculations, and visualization."
Power Query (M Language),"Data extraction, transformation (ETL), cleaning, and merging source files."
DAX,"Creating complex measures (KPIs, time intelligence, rolling averages) and calculated columns."
CSV / Excel,Data source files for the project.

📁 Repository Structure
├── data/
│   ├── Orders.csv                   # Transaction data with Order ID, Customer, Location
│   └── Details.csv                  # Item-level data with Amount, Profit, Quantity, Category
├── images/
│   └── dashboard_preview.png        # Screenshot of the final dashboard 
├── Madhav_Sales_Dashboard.pbix      # The main Power BI Desktop file
└── README.md                        # This file


🚀 Getting Started
To view and interact with the full dashboard, follow these steps:

Download Power BI Desktop: Ensure you have the latest version of Power BI Desktop installed on your system.

Clone the Repository:

Open the File: Double-click the file named Madhav_Sales_Dashboard.pbix.

Refresh Data: If prompted, ensure the Power BI file can successfully link to the .csv files located in the data/ folder.

🔗 Live Web View (Optional): You can also view the published version of the report on Power BI Service here: [[Insert Power BI Service Publish Link Here]]


💡 Project Learnings
During the development of this dashboard, I gained practical experience in:

Building a robust star schema data model in Power BI.

Implementing time intelligence functions using DAX (e.g., Year-over-Year growth).

Creating a cohesive UI/UX focusing on simplicity and clarity for business users.

Utilizing cross-filtering and drill-through actions to enable deep data exploration.

![Alt Text](https://github.com/sumansamantapku-rgb/Madhab-Ecommerce-Sales-Dashboard-build-using-PowerBi/blob/main/Screenshot%202025-11-08%20102444.png?raw=true)
![Alt Text](https://github.com/sumansamantapku-rgb/Madhab-Ecommerce-Sales-Dashboard-build-using-PowerBi/blob/main/Screenshot%202025-11-08%20102503.png?raw=true)
🤝 Contribution
If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request!
