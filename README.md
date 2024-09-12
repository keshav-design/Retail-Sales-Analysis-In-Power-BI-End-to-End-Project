# Retail-Sales-Analysis-In-Power-BI-End-to-End-Project

Overview :-
This project is designed to provide a comprehensive analysis of retail sales data using Power BI. The goal of this project is to enable users to gain actionable insights into sales performance across different dimensions, including geography, product categories, and sales representatives.

In this project, i have work with a variety of datasets, perform data cleaning and modeling, and use DAX calculations to derive meaningful metrics. Additionally, i have implemented Row-Level Security (RLS) to ensure that users only have access to data pertinent to their region.

Datasets :-
The following datasets are used in this project:

Sales (folder by year): Contains sales data organized by year.

Categories (Excel): Provides information about product categories.

Geography (Excel): Includes geographical data related to sales regions.

Product (CSV/Database): Contains detailed product information.

SalesRep (Excel): Lists sales representatives and their details.

SubCategories (Excel): Details the subcategories of products.

Steps :- 

1) Data Cleaning

Imported and merged datasets from various sources.

Handled missing values, corrected inconsistencies, and standardized formats.

Removed duplicate records and outliers.

2) Data Modeling

Created relationships between tables (e.g., linking Sales data with Product, Categories, and Geography).

Developed a star schema model to facilitate efficient querying and reporting.

3) DAX Calculations

Total Revenue: Calculated the sum of all sales transactions.

Total Cost: Computed the total cost incurred in sales transactions.

Gross Profit: Derived by subtracting total cost from total revenue.

Gross Profit MoM Growth %: Analyzed month-over-month growth in gross profit.

Average Sales per Day: Determined the average sales amount per day.

Breakdown Analysis by Product: Analyzed sales performance across different products.

QoQ Growth %: Calculated quarter-over-quarter growth percentage.

4. Row-Level Security (RLS)

Implemented RLS on the "Country" column to restrict data visibility. Users can only access data relevant to their assigned country and cannot view data from other countries.


Calculations :- 

Total Revenue: Sum of all sales values.

Total Cost: Sum of all associated costs.

Gross Profit: Total Revenue - Total Cost.

Gross Profit MoM Growth %: ((Gross Profit of Current Month - Gross Profit of Previous Month) / Gross Profit of Previous Month) * 100

Average Sales per Day: Total Revenue / Number of Days in the Period.

Breakdown Analysis by Product: Detailed analysis of sales by product type.

QoQ Growth %: ((Total Revenue of Current Quarter - Total Revenue of Previous Quarter) / Total Revenue of Previous Quarter) * 100

Conclusion :- This project provides a robust framework for analyzing retail sales data using Power BI. By integrating multiple datasets and applying advanced DAX calculations, we are able to uncover valuable insights into sales performance and growth trends. The implementation of Row-Level Security ensures that sensitive data is protected, allowing for secure and tailored access to regional sales information.
