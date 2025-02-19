# Toys Shop Business Report

- [Brief Overview of the Dataset](#brief_overview_of_the_dataset)
- [Tasks](#tasks)
- [Tool](#tool)
- [Data Cleaning](#data_cleaning)
- [Data Modelling and DAX](#data_modelling_and_dax)
- [Findings](#findings)
- [Recommendations](#recommendations)

## Brief Overview of the Dataset

The retail dataset is a combination of time series and geospatial data. The dataset contains four independent dimension/lookup tables and a sales table with more than 820,000 observations. 

It includes information on total profit, revenue, unit sales, profit margins, product and store performance by location, inventory records, and other key performance indicators like monthly orders, revenue, and profit compared to previous goal levels. The inventory records display the current stock and out of stock produccts.

## Tasks

- Track KPIs (sales, revenue, profit, and inventory)

- Find the product categories that drive the biggest profits, and find out if they are the same across store locations.

- Analyze any seasonal trends in profit and forecasts.

- Find out how much money the toy stores have invested in inventory and how long it will last.

- Determine whether out-of-stock products are causing sales losses at specific locations.

## Tool

- Power Query
- Power BI
- Excel

## Data Cleaning

- The datasets were imported into the power query editor from their respective excel files. All columns were formatted to the right datatypes. Created a calendar table comprising monthly, quarterly, and yearly sales to perform robust time intelligence functions and analysis.

## Data Modelling and DAX

![J](https://github.com/user-attachments/assets/db87c050-d3da-412f-a794-903bba49bbdf)

- I connected to the independent source tables on Power BI and shaped and performed numerous transformations on each table in the Query Editor.

![I](https://github.com/user-attachments/assets/772566b5-61ef-45d3-a52d-1dfe6fd396a2)

- On the data view, I created table relationships and a relational model (Star and Snowflake database schema) with one-to-many relationship cardinality and a single filter direction flowing downstream.
  
- Added calculated fields with Data Analysis Expression (DAX) and organized my dashboard in the report view with important KPIs, filters (drill-through and visual filters), and tables.

![Screenshot 2024-09-03 095419](https://github.com/user-attachments/assets/474b73e4-84d0-4021-97e2-8132d7895fc4)

- Performance Note

![Performance Note](https://github.com/user-attachments/assets/7182d281-cef6-4142-aa77-580b06a1c1e6)

## Findings

- Toys and electronics were the most profitable categories, generating $1.01M and $1M, respectively, with toys contributing 26.89% of total profit. Profits were highest at Downtown/Residential (toys) and Airport/Commercial (electronics) stores.

- Q2 led with $1.19M in profit, surpassing Q4 by 94.17% and contributing 29.88% of overall profit.

- Toy stores generated $132K in revenue from inventory, which sells out in less than a month.

- Stockouts had no negative impact on sales, as stores with the most out-of-stock products saw higher sales.

## Recommendations

- Enhance inventory management by implementing predictive restocking to prevent shortages and maximize toy sales, especially at high-performing locations.
- Leverage stockout trends by using limited-stock promotions to create urgency and boost demand while refining pricing and inventory strategies.

