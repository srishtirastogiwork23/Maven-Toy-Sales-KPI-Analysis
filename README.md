# 🎯 Maven Toy Sales KPI Analysis Dashboard

<img width="2732" height="1365" alt="image" src="https://github.com/user-attachments/assets/f1177d1a-bb61-4f73-ab41-583b643c6ec9" />

### Project Overview
This repository contains the files for an interactive Power BI dashboard focused on Sales KPI Analysis for a toy retail business (inferred as "Maven Toy Sales"). The primary goal of this project is to provide a clear, real-time snapshot of the company's operational and financial health across key metrics.

The dashboard serves as a vital tool for management to:
1. Monitor total sales, revenue, and profit trends over time.
2. Analyze performance by store location and product category.
3. Identify seasonal trends and opportunities for inventory management.

Key Insight Focus: Financial performance tracking, temporal trend analysis, and product/location segmentation.

### 📊 Dashboard Key Metrics and Features
The dashboard is designed for high-level monitoring and deep-dive analysis, primarily focused on Orders, Revenue, and Profit.

#### 1. Key Performance Indicators (KPIs)
The top row presents crucial aggregated metrics, with a surrounding area chart showing historical trends for context:
1. Total Orders by Month: The aggregate number of transactions over the observed period.
2. Total Revenue by Month: The total sales value generated.
3. Total Profit by Month: The total gross profit achieved.

#### 2. Analytical Visualizations
Orders by Product Category (Bar Chart): Ranks product categories (Toys, Art & Crafts, Games, Sports & Outdoors, Electronics, etc.) by the total number of orders. This highlights which product lines are driving the highest transaction volume.

1. Revenue by Month (Line Chart): A detailed time-series analysis showing the fluctuation of revenue over the full historical period (e.g., Jan 2022 to Jul 2023). This is essential for identifying seasonality, growth phases, or decline periods.
2. Revenue (M) by Order Month (Bar Chart): A monthly breakdown of total revenue, typically used to show performance degradation or success in recent months.

#### 3. Interactive Filtering
Store Location Slicer: A crucial filter that allows users to instantly segment all dashboard visuals by the operating environment:
1. Airport
2. Commercial
3. Downtown
4. Residential
This enables location-based performance comparison and strategic planning.

### 🛠️ Tools and Technologies
1. Primary Tool: Microsoft Power BI Desktop
2. Data Preparation: Power Query Editor for connecting to the data source, ensuring data quality, and creating date-related calculated columns.
3. Calculations: Data Analysis Expressions (DAX) for computing core measures like Total Orders, Total Revenue, Total Profit, and time-based aggregates.

### 🚀 Getting Started
To explore this interactive dashboard locally:
1. Clone the Repository: Download or clone the contents of this repository.
2. Install Power BI Desktop: Ensure you have the latest version of Microsoft Power BI Desktop installed.
3. Open the File: Locate and open the .pbix file.
4. Interact: Use the Store Location slicer on the left to filter the entire view and compare sales performance across different operating environments. Observe the month-over-month changes in the Revenue and Profit trend charts.
