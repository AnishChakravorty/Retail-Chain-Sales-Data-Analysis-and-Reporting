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
![image](https://github.com/user-attachments/assets/48cdffef-96c4-4781-8624-0248016ace31)


## Insights

### Retail Transaction Dashboard 

1. Overall Performance:

- Total Transaction amount: 812237
- Count of customer_id: 124959
- Average Transaction: 64.9951428
- Customer Response: 13842


2. Monthly Trends:

- The "Month year vs Transaction amount" chart shows consistent transaction levels from 2011 to early 2015, with a significant drop at the end of the period.
- The "Month vs Transaction amount" bar chart indicates some monthly variation, with peaks in months 1, 6, and 7 (likely January, June, and July).


3. Top Customers:

- The "Top 10 Customer_id count" chart shows the most frequent customers, with CS4424 having the highest transaction count.
-"Top 10 Customers by Response" displays a fairly even distribution among the top responders, each accounting for around 32-33% of responses.


4. Customer Value:

- The "Top 10 customers vs Transaction amount" chart shows CS3752 as the highest-value customer, followed closely by CS3555 and CS6109.


5. Customer Behavior:

- There's a discrepancy between transaction frequency and transaction amount. The customers with the most transactions are not necessarily those with the highest transaction amounts.


6. Seasonality:

- The monthly transaction amounts suggest some seasonality in the business, with higher volumes in certain months.


7. Customer Base:

- With 124,959 unique customer IDs, the business has a large customer base, but the top 10 charts indicate that a small portion of customers contribute significantly to transactions and responses.


8. Response Rate:

- The customer response figure (13,842) compared to the total customer count suggests that only about 11% of customers are actively responding or engaging with the business in some way.

### Additional Analysis 

1. Frequency vs Monetary: There's a strong positive correlation between frequency of purchases and monetary value. As customers make more purchases, they tend to spend more overall.

2. Customers vs Month:

- Peak customer activity is in February (1715 customers)
- There's a significant drop in March (1330 customers)
- The lowest point is in April (39 customers)
- Customer numbers gradually recover from May to December


3. Customer Segmentation:

- Monetary: 80% of revenue comes from segment P0, while 20% comes from P2
- Frequency: 74% of purchases are made by segment P0, while 26% are from P2


4. Frequency vs Customers: The top 10 customers by frequency are shown, with CS4424 having the highest purchase frequency at 39.

5. Seasonal Trends: The Customers vs Month chart suggests strong seasonality in the business, with a peak in winter and a trough in spring.

6. Customer Concentration: The Frequency vs Customers chart implies that a small number of high-frequency customers contribute significantly to the business.


