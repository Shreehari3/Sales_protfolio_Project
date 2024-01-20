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
**Step 1:** Added Power BI connectivity and loaded data into a MySQL database.

**Step 2:** examined and eliminated the Power BI-created default database relationships. created the necessary Power Query dimension tables.

**Step 3:** Compared values with the supplied data, validated data in Power BI.

**Step 4:** Data transformation, which includes the construction of a dynamic table for the previous sales month.

**Step 5:** combined tables and created calculated columns in Power Query, such as `fiscal_year}.

## Building The Dashboard
I have created 5 different report views in this report which serves the need of various stakeholders. Let’s have a look at each of them.

The first page of the report is a home page with the navigation to all other views and a summary of each page so a user can directly access the report they need to look at.
Finance View
The Finance View shows the P & L statements. The Top Performing and Bottom Performing products and customers. Different product segment performances in different regions. The most important metric here is it shows the Year on Year comparison of P & L in a single view.

There is one button created for this view which displays the Net Sales performance Vs Last Year and Vs Target. This helps in decision-making by comparing past performance with the target to achieve the desired goals.

Sales View
The sales view is for the sales team to drill down the performance of each product and customer in individual regions. Similar to the finance view it does have the same filters to provide in-depth analysis of sales performance.

Marketing View
Marketing View contains Gross Margin %, Net Profit %, Operational Expenses and Cost Of Goods Sold which are important financial stats that marketing should be aware of. This helps in deciding the marketing budget for each product in a particular market. Marketing will also be aware of the potential customers and potential market and whether there is a scope for business or not.

Supply Chain View
The supply chain is also a very important part of any business which if not planned timely can increase the operating cost. Keeping an inventory involves some cost and similarly not having an inventory and not delivering the products on time can harm the business.

The supply chain team should know about the demand for the products from time to time. So the historical data helps them in making informed decisions. The visual above shows that the forecast accuracy of 80.26% in the first Quarter of the year 2020 was not good as compared to the 85.92% forecast accuracy of the same period in the year 2019. The Accessories is the product segment which suffered the most i.e 51.50%.

Executive View
The Executive view is a consolidated report which includes KIPs like NS, RC%, GM%, NP%, Forecast Accuracy%, Market share and top-selling products and top customers. This view has almost all the important metrics in one view which a top stakeholder will like to see. An executive view saves the time of senior stakeholders who do not want to go in depth about everything but also want to keep abreast with what’s going on in every department.

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

This project taught hings beyond just Power BI. In order to compare the performance of the products, product categories, markets, customers, etc., one must go through the P&L statements in the project's business scenario. Financial statistics are provided, and dashboards measure and show the performance of items across various marketplaces and client segments.

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
  


