☕ Bright Coffee Shop Sales Analysis (BRIGHTLIGHT)
Project Overview
Analysis of transactional data, from previous months, for the new CEO to better understand the position of the company

Welcome to the Bright Coffee Shop Sales Analysis project! The purpose of the analysis is to assist the newly appointed CEO in making strategic decisions to increase revenue and enhance business performance using historical transactional data. By providing key analysis on areas where the business struggles and areas where the business is thriving we can then understand how to fully maximise our strengths while also improving our weaknesses

Objectives
Identify which products generate the most revenue.
Determine the time of day the store performs best.
Discover sales trends across products and time intervals.
Provide strategic recommendations to improve sales performance.
🛠️ Tools & Technologies Used
Coding & SQL Platforms:

Microsoft SQL Server
Databricks / DBeaver / MySQL Workbench / Google BigQuery
Snowflake (for data storage & transformation)
Data Visualization:

Microsoft Excel
Power BI / Tableau / Google Sheets
Presentation Tools:

Microsoft PowerPoint
Canva / Miro / Figma
🧩 Project Tasks
Task 1: Planning & Architecture (via Miro)
Create a Data Flow & Architecture Diagram:

Data source → ETL pipeline → Snowflake (storage) → Visualization tools
Define Key Insights:

Sales by product & time intervals
Revenue generation and product performance
Plan Calculations:

total_amount = unit_price * transaction_qty
Grouping by 30-minute or hourly intervals
Total units sold by product category
Task 2: Data Processing in Snowflake
Convert Excel data to CSV and upload to Snowflake

Perform the following transformations:

Create transaction_time_bucket column (grouped by 30-min or 1-hour intervals)
Properly cast unit_price (e.g., convert '3,1' to 3.1)
Calculate total_amount = unit_price * transaction_qty
Use SQL for grouping & aggregation
Task 3: Data Analysis & Visualization
Export processed data into Excel

Create dashboards or pivot tables showing:

Total revenue per product
Peak sales time intervals
Units sold by category
Best-selling vs underperforming products
Use clear charts and graphs

Task 4: Presentation to the CEO
Deliverables:

Methodology Document (approach & process)

Presentation Slides (key insights & visuals)

Summary of Findings
*There are products that are not being sold as much as others *Some products are underperforming throughout the different intervals of the day while others perform throughout *Other products sales occur at different intervals of the day



Recommendations 💡
Based on these insights, I propose the following recommendations to improve sales performance and operational efficiency:
1.	Optimize the Product Mix: Given the dominance of Coffee and Tea, consider stocking more of the best-selling products within these categories, such as Earl Grey Rg and Dark chocolate Lg, to meet high demand.
2.	Strategic Marketing: Implement marketing campaigns during slow time slots, such as the midday period (12:00 PM to 3:00 PM), to attract customers and boost sales during these lulls. Promotions, happy hour specials, or loyalty program incentives could be effective.
3.	Promote Underperforming Products: Identify products with low sales volumes (e.g., Branded merchandise and Packaged Chocolate) and develop targeted promotions or new product placements to increase their visibility and appeal.

