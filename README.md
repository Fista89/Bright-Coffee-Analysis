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

Recommendations:

Run campaigns during low-traffic times
Stock more of top-selling items
Promote low-performing products
Next Steps:

Automate daily sales reports
Enable performance tracking across locations
Implement loyalty programs during peak hours
Submission Requirements
Miro Plan/Diagram (Data Architecture)
Processed Dataset in Excel or Google Sheets (with Pivot Tables & Charts)
PowerPoint Presentation
SQL Code File (Text Format)
