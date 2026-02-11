📊 Power BI Business Performance Dashboard
📌 Project Overview

This project was developed to transform static Excel-based reporting into a fully interactive and dynamic Power BI dashboard to support business decision-making.

The objective was to centralize data from multiple operational sources, apply professional data modeling techniques, and deliver meaningful KPIs and insights for management.

🎯 Project Objectives

Build a professional and interactive Power BI report

Implement a reliable and optimized data model (Star Schema)

Translate business questions into measurable KPIs

Enable dynamic filtering and segmentation

Deliver actionable insights for strategic decision-making

🏗️ Data Modeling Approach
🔹 1. Data Sources

Data was imported from multiple operational sources including:

Sales / Orders (Fact Table)

Customers

Products

Suppliers

Locations

🔹 2. Data Preparation (Power Query)

Data types validation (Date, Numeric, Text)

Removal of null or duplicate records

Column renaming and standardization

Data transformation and cleaning

🔹 3. Star Schema Implementation

A proper Star Schema was implemented:

Central Fact Table: Sales

Dimension Tables:

Customers

Products

Suppliers

Locations

Date Table

Relationships:

One-to-Many

Single direction filtering

Primary key → Foreign key structure

🔹 4. Date Table (DAX)

A custom Date Table was created using DAX to enable time intelligence:

Year

Month

Month Number

Quarter

Full Date hierarchy

Marked as official Date Table in the model.

📊 Key KPIs & Measures (DAX)

Main measures created:

Total Sales

Total Quantity

Average Delivery Time

Sales Last Year

Growth %

Top 5 Suppliers / Products

Performance comparisons by segment and period

Time intelligence functions used:

SAMEPERIODLASTYEAR

CALCULATE

DIVIDE

TOPN

📈 Dashboard Visualizations
🔹 Top 5 Suppliers / Products (Bar Chart)

Displays top-performing entities

Dynamic subtitle showing cumulative value

Automatically reacts to filters and slicers

🔹 Trend Analysis (Line Chart)

Sales evolution over time

Trend line added to identify growth patterns

🔹 Category Distribution (Donut Chart)

Visual representation of contribution by category

Percentage breakdown of total performance

🔹 KPI Cards

Dynamic indicators:

Total Sales

Total Orders

Average Delivery Time

Growth %

All KPIs react to slicers and filters.

🔹 Matrix & Conditional Formatting

Performance by Customer / Product / Supplier

Conditional formatting:

Color scale

Icons (↑ ↓ ⚠)

Threshold indicators

🎛️ Advanced Features Implemented

Interactive slicers (Date, Region, Category, Supplier)

Bookmarks for navigation and storytelling

Custom tooltips with additional details

Drill-down functionality

Cross-filtering between visuals

Professional theme and consistent UI design

📌 Business Questions Answered

Who are the Top 5 performing suppliers/products?

Which product category generates the highest activity?

Which region contributes the most to performance?

How do delivery delays impact overall performance?

Which segments require strategic attention?

🔍 Key Insights (Example)

Top 5 suppliers contribute to a significant portion of total sales → High dependency risk.

One product category dominates revenue but shows declining growth trend.

Certain regions show strong volume but longer delivery times impacting efficiency.

🚀 Deployment

Published to Power BI Service

Interactive navigation enabled

Report optimized for usability and performance

🛠 Tools Used

Power BI Desktop

Power BI Service

DAX (Data Analysis Expressions)

Power Query

Star Schema Data Modeling

📂 Project Deliverables

Structured .pbix file

Published interactive report

GitHub repository with documentation

Business insight summary with recommendations

👤 Author

Developed as part of a professional Business Intelligence project focused on decision support and advanced Power BI analytics."# MEDINCODEX-Plants-data-analysis-with-PBI" 
