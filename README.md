# Toys Shop Business Report

- [Brief Overview of the Dataset](#brief_overview_of_the_dataset)
- [Tasks](#tasks)
- [Tool](#tool)
- [Processes](#processes)
- [Key Inisghts](#key_insights)
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

- I connected to the independent source tables on Power BI and shaped and performed numerous transformations on each table in the Query Editor.

- On the data view, I created table relationships and a relational model (Star and Snowflake database schema) with one-to-many relationship cardinality and a single filter direction flowing downstream.

- Added calculated fields with Data Analysis Expression (DAX) and organized my dashboard in the report view with important KPIs, filters (drill-through and visual filters), and tables.


## Dashboard and Pivot Table

![Pivot table](https://github.com/user-attachments/assets/9c3ace19-9a27-4ac8-b854-12d8595b9d79)

![New](https://github.com/user-attachments/assets/6ac0eafb-4f5c-41f5-9c4c-88b31be7004a)

## Key Insights

- Maven Coffee's revenue showed a steady increase from January to June, peaking at $166.49k in June, with a slight dip in February to $76.15k.
  
- Weekday sales outperformed weekends, with Monday generating the highest revenue ($101.68k), while Saturday and Sunday had the lowest ($96.89k and $98.33k).
  
- Coffee products were the best-selling items, totaling 89,250 orders and generating $269.95k in revenue, while packaged chocolate had the lowest sales (487 orders).
  
- Hell’s Kitchen led in revenue with $236.51k, followed by Astoria and Lower Manhattan.

## Recommendations

- Introduce weekday promotions for lower-selling products to capitalize on higher weekday traffic and encourage upselling.
  
- Launch weekend marketing campaigns or special discounts to boost sales on Saturdays and Sundays when revenue is lower.
  
- Expand high-performing coffee product offerings or introduce premium variations to maximize revenue from the most popular category.


