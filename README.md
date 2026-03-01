📊 Sales_Revenue Dashboard – Power BI
🔍 Project Overview
Sales_Revenue is a Power BI dashboard project focused on analyzing total revenue performance across different categories, time periods, and business segments.
This project helps in understanding:
Overall revenue trends
Category-wise sales performance
Monthly and yearly growth
Profitability insights
Revenue contribution analysis
🎯 Business Objective
The main objective of this dashboard is to:
Monitor total revenue performance
Track profit and margin
Identify high-performing categories
Analyze Year-over-Year growth
Support data-driven business decisions
🗂 Data Model
This project follows a clean and optimized Star Schema Model.
📌 Fact Table – Sales
Date
Category
Units Sold
Sale Value
Cost Value
Profit (Calculated Column)
Profit %
📌 Dimension Tables
Category Table
Date Table (Year, Month, Quarter)
🔗 Relationships
Category → Sales (One-to-Many)
Date → Sales (One-to-Many)
📐 Calculated Columns
Clean Category
Year
Month Name
Quarter
Profit
Profit %
Revenue Band
📊 Key DAX Measures
Total Revenue = SUM(Sales[Sale Value])
Total Cost = SUM(Sales[Cost Value])
Total Profit = [Total Revenue] - [Total Cost]
Profit Margin % = DIVIDE([Total Profit], [Total Revenue])
Revenue YTD
Revenue LY
Revenue Growth %
📈 Dashboard Features
KPI Cards (Revenue, Profit, Margin %)
Monthly Revenue Trend (Line Chart)
Category-wise Revenue (Bar Chart)
Revenue Share % (Donut Chart)
Year & Category Slicers
Dynamic Filtering
🛠 Tools Used
Power BI Desktop
DAX
Excel / CSV Dataset
Data Modeling
🚀 How to Use
Download the .pbix file.
Open in Power BI Desktop.
Refresh the dataset.
Use slicers to analyze revenue by category and year.
Explore trends and insights.
📊 Insights Generated
Identified top revenue-generating categories
Measured profit margins
Tracked seasonal trends
Compared Year-over-Year performance
Analyzed revenue contribution %
