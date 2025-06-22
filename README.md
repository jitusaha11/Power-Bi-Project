# Power-Bi-Project
An interactive Power BI dashboard project analyzing sales, profit, and operational metrics for a multinational retail company. Focused on uncovering actionable insights across regions, categories, shipping modes, and customer segments.
# 📁 Project Overview
This project explores transactional and operational data from Global Superstore (2016–2019) to guide business decisions on revenue growth, margin improvement, customer segmentation, and logistics performance. The outcome is a fully interactive Power BI report supporting multi-level analysis.

# 📄 Data Description
The dataset includes three primary tables:

Table	Description
Orders	Transaction-level data: order date, sales, discount, profit, quantity
Returns	Returned orders for exception analysis
People	Customer segments (Consumer, Corporate, Home Office)
Key fields used in the analysis:

Order Date, Ship Date, Ship Mode
Region, Country, City
Category, Sub-Category, Product Name
Sales, Discount, Profit, Quantity
🧹 Data Modeling & Cleaning
Designed a Star Schema with Date, Product, Customer, and Shipping dimensions.
Calculated columns and measures:
Order Lead Time = Ship Date – Order Date
Profit Margin (%), Average Discount, YOY Growth
Discount-to-Profit Correlation
Ensured clean joins between fact and dimension tables.
# 📈 Analysis Highlights
1. Revenue & Profit Trends
Year-over-year growth in sales and profit
High-performing vs. underperforming categories and regions
2. Discount Strategy
Analyzed profit margins across discount brackets
Identified thresholds where discounting erodes profitability
3. Logistics & Delivery
Measured average lead time by shipping mode and region
Flagged late shipments and returns for corrective action
4. Customer Segmentation
Compared spend and profit by segment: Consumer, Corporate, Home Office
Uncovered high-LTV customer profiles
# 📊 Dashboard Features
Interactive filters for Region, Segment, and Category
Visuals used:
KPI Cards, Line Charts, Bar Charts
Heatmaps, Scatter Plots, Box Plots
Filled Maps (Profit Margin % by location)
Slicer-driven segment comparison
Drill-through enabled for detailed views
# 💡 Key Insights
Deep discounts (>30%) consistently lead to negative margins in Technology category.
Standard Class shipping has the lowest cost but highest delay rate in APAC.
Corporate customers have higher average spend but more returns compared to Home Office.
East and Central regions outperform in Furniture and Office Supplies; APAC under-indexes.
# 📎 Files Included
✅ Global_Superstore_Data.xls – Source data
✅ Global_Superstore_Data_Analysis.pbix – Power BI dashboard file
# 🛠 Tools Used
Microsoft Excel (Pre-processing)
Power BI (Data Modeling, DAX, Visualizations)
DAX Measures & Calculated Columns
