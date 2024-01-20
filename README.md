# Business Insights Project
## Table of Contents
1. [About AtliQ Hardware](#about-atliq-hardware)
2. [Problem Statement](#problem-statement)
3. [Management’s Dashboard Requirements](#managements-dashboard-requirements)
4. [Dashboard Created (Dynamic Dashboard)](#dashboard-created-dynamic-dashboard)
5. [Project Execution](#project-execution)
6. [Building The Dashboard](#building-the-dashboard)
7. [Tools Used In Project](#tools-used-in-project)
8. [Learnings From Project](#learnings-from-project)
9. [Power BI Features Learned & Used](#power-bi-features-learned--used)

## About AtliQ Hardware
Hardware such as PCs, mice, printers, and other items are manufactured and sold by AtliQ Hardware to numerous businesses worldwide. Companies like Croma, Amazon, Neptune, Staples, Walmart, and others are among AtliQ's clients; these clients include both physical stores and e-commerce platforms.

## Problem Statement
There are difficulties for AtliQ Hardware in the Latin American market. Traditionally, MS Excel's limited data analysis skills were used to make decisions based on surveys and gut feeling. More complex data analysis is required as a result of the company's expansion and the rise in data that is readily available. Thus, AtliQ has made the choice to appoint a Data Analyst in order to make use of this data in order to make precise and knowledgeable business judgments.

## Management’s Dashboard Requirements
The following Power BI Dashboard views are required by management:
- **Finance View:** Present profit and loss figures for all markets, consumers, and products.
- **Sales View:** Display important metrics for both top- and bottom-performing clients.
**Marketing View:** Product-focused and comparable to Sales View.
**Supply Chain:** Evaluate the correctness and dependability of the supply chain's performance.
- **Executive View:** A comprehensive overview of important findings for top management.

## Dashboard Created (Dynamic Dashboard)
This Power BI project is a practical course with real-life business scenarios, including recorded business meetings with stakeholders. The project involved iterative feedback, feature changes and additions to ensure the dashboard provides all necessary key metrics in a consolidated format.

## Project Execution

### Step 1: Data Loading
- Loaded the data into a MySQL Database.
- Established a connection between the MySQL Database and Power BI.

### Step 2: Database Relationship Review
- Reviewed and deleted the default database relationships created by Power BI.
- Created required dimension tables in Power Query.

### Step 3: Data Validation
- Performed data validation in Power BI by comparing tables with the provided data.

### Step 4: Data Transformation
- Transformed data, for example, by creating a dynamic Last Sales Month Reference table that updates after each sale.

### Step 5: Creating Calculated Columns
- Created calculated columns in Power Query, such as `fiscal_year`.
- Merged tables after creating calculated columns.

### Step 6: Data Modeling
- Employed data modeling techniques, specifically using a Star Schema.
- Connected all dimension tables with Fact tables for efficient data analysis.

### Step 7: Advanced DAX Formulas
- Created calculated columns using over 40 DAX formulas.
- Validated these columns against the MySQL database or Excel files for accuracy.

### Step 8: Report Optimization
- The final step before dashboard design and construction.
- Optimized the Power BI report to reduce the overall file size, making it easier to share and access.


## Building The Dashboard
### 1. Home Page
- The initial page with navigation links to all other report views.
- Summaries of each view for quick access to needed reports.

### 2. Finance View
- Displays profit and loss (P&L) statements.
- Highlights top and bottom performing products and customers.
- Compares product segment performances across regions.
- Features year-on-year P&L comparison.
- Includes a button to compare Net Sales performance against the previous year and targets.

### 3. Sales View
- Tailored for the sales team to analyze product and customer performance by region.
- Provides similar filters to the Finance View for detailed sales analysis.

### 4. Marketing View
- Focuses on key financial stats like Gross Margin %, Net Profit %, Operational Expenses, and Cost Of Goods Sold.
- Assists in marketing budget planning and identifying potential markets and customers.

### 5. Supply Chain View
- Addresses supply chain management and planning.
- Highlights inventory costs and the impact of delivery delays.
- Uses historical data for demand forecasting and supply chain optimization.
- Features a comparison of forecast accuracy across different periods.

### 6. Executive View
- A consolidated report for top-level stakeholders.
- Includes key performance indicators (KPIs) like Net Sales, Return on Capital, Gross Margin, Net Profit, Forecast Accuracy, Market Share, and top-selling products and customers.
- Provides a comprehensive overview for senior stakeholders to stay informed on all departmental performances.

## Tools Used In Project
- MS Excel
- MySQL
- Power BI
- Power BI Service
- DAX Studio

## Learnings From Project
- Power BI
- Data Modelling
- Dashboard Creation & Designing
- Project Charter
- Stakeholder Mapping
- Going through P&L Statements
- Working on business transactions like creating Profit %, Gross Margin %, Forecast %, comparison in sales from previous periods, etc. (All listed below in the DAX Formulas list)

This project taught things beyond just Power BI. To compare the performance of the products, product categories, markets, customers, etc., one must go through the P&L statements in the project's business scenario. Financial statistics are provided, and dashboards measure and show the performance of items across various marketplaces and client segments.

## Power BI Features Learned & Used
- DAX Formulas (Listed at the bottom)
- Data Modeling
- Table Creation
- Creating Tool Tips
- Creating Switch using Bookmark
- Creating Dynamic Titles
- Learnt using conditional formatting for the blank results after applying filters
- Creating Dynamic Last Refresh Date
- Creation Of Different Views in a single report for different departments
  


