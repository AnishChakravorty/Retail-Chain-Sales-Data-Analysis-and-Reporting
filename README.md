# Retail-Chain-Sales-Data-Analysis-and-Reporting

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Project Phases](#project-phases)
  - [Phase 1: Data Collection and Database Setup](#phase-1-data-collection-and-database-setup)
  - [Phase 2: Data Cleaning and Preparation](#phase-2-data-cleaning-and-preparation)
  - [Phase 3: Data Analysis](#phase-3-data-analysis)
  - [Phase 4: Reporting](#phase-4-reporting)
- [Dashboard](#dashboard)
- [Insights](#insights)


## Project Overview
To analyze sales data and generate meaningful reports for a retail chain using Python, SQL, and Excel. The analysis includes data collection, database setup, data cleaning and preparation, exploratory data analysis, and report generation.

## Data Source

It includes the following fields:

- TransactionID: A unique identifier for each transaction
- TransactionTime: The time the transaction took place
- ItemCode: The code of the item purchased
- ItemDescription: A description of the item purchased
- NumberOfItemsPurchased: The number of items purchased in the transaction
- CostPerItem: The cost per item
- Country: The country where the transaction took place

## Project Phases

### Phase 1: Data Collection and Database Setup

1. Data Collection: Download the data from Kaggle as a CSV file and place it in the `data/` directory.
2. Database Setup: Set up a SQL database to hold the data. Design the database schema and create the necessary tables using SQL DDL commands.

### Phase 2: Data Cleaning and Preparation

1. Data Cleaning: Use SQL queries and Python (pandas) to clean the data, handling missing or inconsistent data, outliers, etc.
2. Data Preparation: Prepare the data for analysis by creating additional calculated fields, such as total sales value, month/year fields for time-based analysis, etc.

### Phase 3: Data Analysis

1. Data Exploration: Use SQL queries and Python (pandas, matplotlib, seaborn) to explore the data and identify trends and patterns.
2. Advanced Analysis: Perform more complex analysis, such as time series analysis for sales trends and cohort analysis for customer behavior.

### Phase 4: Reporting

1. Report Preparation:
   - Tabular Reports: Create summary tables showing sales by product, store, month, etc.
   - Visual Reports: Create charts and graphs showing trends and patterns.
   - Automated Reports: Set up automated reports that run regularly and update Excel dashboards.
2. Report Presentation: Present the findings in an Excel dashboard or prepare a PowerPoint presentation.


## Dashboard

![Excel Dashboard](https://github.com/user-attachments/assets/b0032b40-85af-4fe5-8399-7dfbf5ad8819)
![Excel Dashboard 2](https://github.com/user-attachments/assets/514db744-3fc4-4c2d-8425-7221f7683f76)


## Insights

1. Sales Overview:

- Total Sales: $4.13M
- Total Profit: $503.78K
- Profit Margin: 12.18%
- Total Quantity Sold: 26.73K


2. Sales by Segment:

- Consumer segment leads with 50.52% of sales
- Corporate follows with 30.34%
- Home Office accounts for 19.14%


3. Sales by Category:

- Technology is the top-selling category (35.98%)
- Furniture is second (32.75%)
- Office Supplies is third (31.27%)


4. Sales Trend:

- The line graph shows sales fluctuations over time
- There's a noticeable peak in sales around November-December, suggesting a holiday season spike
- Sales seem to have an overall upward trend over the period shown


5. Top 5 Sub-Categories:

- Phones (21.26%)
- Chairs (20.54%)
- Storage (13.84%)
- Tables (12.59%)
- Binders (10.71%)


6. Regional Sales:

- West region leads in sales with 32.61%
- East follows closely with 28.78%
- Central and South regions have lower sales percentages


7. Top 5 Cities by Sales:

- New York City
- Los Angeles
- Philadelphia
- San Francisco
- Seattle

