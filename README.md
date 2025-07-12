# Superstore-sales-dashboard

A Power BI dashboard designed to provide actionable insights into sales, profit, and order trends using the Superstore dataset. This project highlights revenue drivers across regions, customer segments, and product categories helping business stakeholders make informed decisions.

📌 Project Summary

Retail stakeholders often struggle to pinpoint what’s driving performance or loss across various areas. This dashboard helps uncover:
- Top-performing product categories
- High-value customer segments
- Region-wise revenue breakdown
- Year-on-year sales trends

❓ Problem Statement

To make better inventory, marketing, and logistics decisions, retail decision makers need a clear view of where revenue is coming from and where performance is lagging.

This dashboard was built to:
- Identify sales and profit trends
- Detect underperforming areas
- Visualize customer segmentation and order behavior

🛠️ Tools Used
-Microsoft Excel – For data cleaning and preprocessing  
- Power BI Desktop – For data modeling, DAX, and dashboard design  
- DAX – For creating custom metrics (KPIs)

📋 Steps Taken
1. Data Cleaning
- Removed blanks and irrelevant fields
- Reformatted dates and categories
- Checked for consistency in region and category values
2. Data Modeling
- Defined data types and relationships
- Created key DAX measures:
  DAX
  Total Sales = SUM(Superstore[Sales])
  Total Profit = SUM(Superstore[Profit])
  Total Orders = COUNT(Superstore[Order ID])

3. Visualization

Built one clean and interactive report page containing:
💡 KPI Cards: Total Sales, Total Profit, Total Orders
📊 Bar Charts: Sales by Region, Category
📈 Line Chart: Yearly Sales Trend
🍩 Donut Chart: Sales by Segment
🧠 Text Cards: Key Insights & Suggested Actions
🔘 Slicers: Region, Category, Segment

📌 Key Insights
🏆 Technology category leads in revenue at $836K
👤 Consumer segment contributes $1.16M — the highest share
🌍 West region is the strongest performer with $3.2K sales
📈 Year-on-year sales are growing, with a sharp rise in 2017

📢 Business Recommendations
🔼 Increase inventory for high-demand Technology products
🚚 Expand logistics and inventory to serve the West region
🎯 Run targeted Consumer-focused marketing campaigns
