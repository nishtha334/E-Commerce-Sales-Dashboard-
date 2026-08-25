E-Commerce-Sales-Dashboard

A Power BI business intelligence dashboard designed to analyze sales performance, profitability, orders, quantity sold, returns, regions, product categories, payment methods, shipping methods, and customer/order-related dimensions.

The dashboard provides a high-level executive view of business performance while also allowing users to explore the data using interactive filters.

Table of Contents,
Project Overview,
Objectives,
Key Performance Indicators,
Dashboard Features,
Visualizations,
Interactive Filters,
Key Insights,
Tools and Technologies,
Data Analysis,
How the Dashboard Works,
Project Structure,
How to Use,
Skills Demonstrated,
Future Enhancements,
Limitations.

Project Overview

E-Commerce-Sales-Dashboard- is an interactive Power BI project created to transform raw business data into meaningful and easy-to-understand visual insights.

The dashboard focuses on important business metrics such as:

Total Sales,
Total Quantity,
Total Profit,
Total Orders,
Profit Margin,
Return Rate,
Sales by Category,
Profit by Region,
Sales by Payment Type,
Performance based on shipping and plan-related filters.

The project demonstrates how Power BI can be used for data cleaning, data modeling, KPI creation, visualization, and interactive business
analysis.

Objectives

The main objectives of this project are:
To monitor overall sales performance.
To measure profitability and profit margin.
To analyze order volume and quantity sold.
To identify return-rate patterns.
To compare sales across product categories.
To compare profit across geographical regions.
To understand the distribution of sales across payment methods.
To provide interactive filtering for deeper analysis.
To present business information through an executive-friendly
dashboard.

Key Performance Indicators

The dashboard displays the following headline KPIs:

KPI                    Dashboard Value

Total Sales                 10.23M
Total Quantity                101K
Total Profit                 1.80M
Total Orders                   20K
Profit Margin               17.56%
Return Rate                 49.80%

These values represent the figures visible in the dashboard screenshot and may change when the underlying dataset or filters are changed.

KPI Definitions

Total Sales
Represents the total sales/revenue generated from the available records.

Total Quantity
Represents the total number of units/items sold.

Total Profit
Represents the total profit generated from the analyzed sales.

Total Orders
Represents the number of orders included in the analysis.

Profit Margin
A profitability measure showing profit relative to sales.

Conceptually:
Profit Margin = Total Profit / Total Sales × 100

Return Rate
A measure used to monitor the proportion of orders/items that were returned.

The exact calculation depends on the return-related fields and business rules in the source dataset.

Dashboard Features

1. Executive KPI Summary
The top section provides a quick overview of the business using six major KPIs:

Total Sales,
Total Quantity,
Total Profit,
Total Orders,
Profit Margin,
Return Rate.

This allows users to understand the overall business position without manually reviewing individual charts.

2. Category Analysis

The dashboard includes category-level analysis to compare sales and return performance.

Categories visible in the dashboard include:
Automotive,
Beauty,
Books,
Clothing,
Electronics,
Groceries, etc.
The category filters allow users to focus the dashboard on a specific product category.

3. Regional Profit Analysis

Profit is visualized across geographical regions.
The dashboard includes:
Africa,
APAC,
EU,
LATAM,
US, etc.

This helps users compare regional profitability and identify differences between markets.

4. Payment Type Analysis

A donut chart presents the distribution of sales by payment type.

Payment methods shown include:
Wire Transfer,
PayPal,
Cryptocurrency,
Debit Card,
Credit Card.

This can help analyze customer payment preferences and the contribution of each payment channel.

5. Shipping Analysis

The dashboard includes an interactive shipping-method filter with options such as:

First Class,
Same Day,
Second Class,
Standard Class.

This can be used to investigate how different shipping methods affect the selected business metrics.

6. Plan Type Analysis

The dashboard also provides a plan-type filter:
Basic,
Enterprise,
Premium.

Users can use this filter to compare business performance across different plan segments.

Visualizations

The dashboard contains several visual elements.

Return Rate by Category: 
A column/bar visualization is used to examine return-rate performance for the selected category.

Total Sales by Category: 
A horizontal bar chart compares total sales across product categories.

This makes it easier to identify which categories contribute the most to revenue.

Total Profit by Region: 
A column chart compares profit across:

Africa,
APAC,
LATAM,
EU,
US.

This visualization supports geographical performance analysis.

Total Sales by Payment Type: 
A donut chart shows how total sales are distributed across different payment methods.

Interactive Filters: 
The dashboard provides slicers that allow users to dynamically filter the report.

Category Filter: 
Filters the report by product category.

Region Filter: 
Filters the report by geographical region.

Shipping Method Filter: 
Filters results according to shipping method.

Plan Type Filter: 
Filters results according to plan type.

Because the dashboard is interactive, selecting a value in one filter can update the other visualizations according to the Power BI relationships and visual interactions configured in the report.

Key Insights

Based on the dashboard view shown in this project:
The dashboard reports 10.23M in total sales.
The business has 101K total quantity represented in the dashboard.
Total profit is approximately 1.80M.
The dashboard contains approximately 20K total orders.
The displayed profit margin is 17.56%.
The displayed return rate is 49.80%.
Sales are compared across multiple product categories.
Profit is compared across five geographical regions.
Payment methods are analyzed using a donut chart.
Interactive slicers make it possible to perform category, regional, shipping, and plan-level analysis.

These observations are based on the current dashboard view. Additional conclusions should be validated against the underlying dataset and business definitions.

Tools and Technologies

Power BI

The dashboard was developed using Microsoft Power BI.

Power BI was used for:
Data visualization,
KPI cards,
Interactive slicers,
Charts and graphs,
Data analysis,
Dashboard design,
Business intelligence reporting,
Data Analysis Concepts.

The project demonstrates concepts including:

Data aggregation,
KPI analysis,
Category analysis,
Regional analysis,
Profitability analysis,
Return analysis,
Payment-method analysis,
Interactive filtering,
Business reporting.

Data Analysis

The dashboard converts transactional/business data into aggregated measures that can be used for decision-making.

Typical analytical dimensions used in the dashboard include:
Category,
Region,
Shipping Method,
Plan Type,
Payment Type.

The dashboard then evaluates business measures such as:
Sales,
Quantity,
Profit,
Orders,
Profit Margin,
Return Rate.

This dimensional approach allows the same metrics to be analyzed from multiple perspectives.

How the Dashboard Works

The general workflow of the project is:
Raw Business Data
        |
        v
Data Preparation
        |
        v
Data Modeling
        |
        v
Calculated Measures / KPIs
        |
        v
Power BI Visualizations
        |
        v
Interactive Dashboard
        |
        v
Business Insights

Step 1: Data Preparation: 
The source data is prepared for analysis by ensuring that the required fields have appropriate data types and usable values.

Step 2: Data Modeling: 
Relevant fields are organized so that Power BI can aggregate and filter the data efficiently.

Step 3: KPI Creation: 
Business metrics such as sales, profit, orders, profit margin, and return rate are calculated or aggregated.

Step 4: Visualization: 
The measures are represented through KPI cards, bar charts, column charts, donut charts, and slicers.

Step 5: Interactive Analysis: 
Users can select categories, regions, shipping methods, or plan types to investigate specific segments.

Project Structure

GitHub repository structure is:
E-Commerce-Sales-Dashboard-/
│
├── README.md
│
├── assets/
│   └── dashboard.png
│
├── powerbi/
│   └── sales-profit-analysis.pbix
│
├── data/
│   └── README.md
│
└── .gitignore

How to Use
Option 1: Open the Power BI File.

Install Microsoft Power BI Desktop.

Clone or download this repository.

Open the .pbix Power BI project file.

If Power BI asks for the data source, reconnect it to the appropriate dataset.

Refresh the data if required.

Use the slicers to explore the dashboard.

Option 2: View the Dashboard Screenshot

If you only want to see the final dashboard, open:
assets/dashboard.png

Skills Demonstrated

This project demonstrates the following technical and analytical skills:
Data Visualization,
Dashboard design,
KPI cards,
Bar charts,
Column charts,
Donut charts,
Interactive slicers,
Data Analysis,
Sales analysis,
Profit analysis,
Regional analysis,
Category analysis,
Return-rate analysis,
Payment-method analysis,
Business Intelligence,
KPI monitoring,
Performance comparison,
Interactive reporting,
Business-focused data storytelling,
Executive dashboard design,
Power BI,
Report creation,
Visual configuration,
Filters and slicers,
Measures and aggregations,
Interactive report development,

Limitations

The dashboard is dependent on the quality and completeness of the underlying dataset.

KPI values can change when filters are applied.

The exact return-rate calculation depends on the business definition and source fields.

The project does not include a detailed data dictionary because the underlying source schema was not provided with the dashboard screenshot.

Large datasets may require optimization of the Power BI data model and measures.

GitHub Repository Setup
The recommended structure is:

README.md-
assets/
powerbi/
data/
.gitignore

Nishtha Sharma
B.Sc. Artificial Intelligence and Data Science,
GitHub:(https://github.com/nishtha334 )
LinkedIn: linkedin.com/in/nishtha-sharma01.

License

This project is intended for educational and portfolio purposes.
If you plan to publish the source code and dataset publicly, add an appropriate open-source license and verify that you have permission to redistribute any included data.

Acknowledgments
This project was created as a practical Business Intelligence and data visualization project using Microsoft Power BI.

The dashboard demonstrates how business data can be transformed into interactive visual reports that support data-driven decision-making.
