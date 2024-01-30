## Overview
This Bestseller Report contains various key metrics related to specific products of a luxury furniture retailer. This report was created with the aim of helping the Purchasing department for data-driven decision making. This report is important because the delivery of a product may take between 3 to 5 months so the Pruchasing department needs to understand which products are performing well and how soon the stock might finish.
  

## Project Objectives
The primary objectives of this report are:
1. To provide the revenue and the Brutto Income for each of these products. This is also time-filtered as we have data from 2018 until current date
2. To determine the number of items sold within a specific period in addition to the current availability within our current stock.
3. To determine the number of items sold for each store as the company is operating in various countries such as Germany, France, Switzerland and so on.
4. To explore the correlation between the time of the year and the type of products that are performing well.
5. To discover the products that are doing well and place orders in advance so that the stock doesn't run out before the new one arrives.
6. To identify the product managers with the largest revenue provided.

## Key Metrics
The key metrics analyzed in this report include:
- Revenue
- Brutto Income
- Items Sold
- No. of Orders
- Revenue (Weighted)
- Available Sotck

## Data Sources
The data used in this analysis is a bit more complex:
- The company has an active database.
- Using this active database, two SQL queries are used in order to pull the data from it.
- Following that, a Python script is created that is joining the two scripts and the result of that is an Excel file that is used as a static database.
- Lastly, another Python script has been created that refreshes this Excel file once a week in order to have the most up-to-date information.
- The reason for this complex database is because the company doesn't have a static database from which data can be pulled directly.


## Project Structure
The project code and analysis are organized as follows:
- SQL queries for data extraction and analysis
- Power BI visualizations
- README file (you are here): [README.md](README.md)

## Results and Insights
The analysis of this data reveals several key insights, including:
- A comprehensive overview of revenue and Brutto Income for each product. The data is time-filtered, covering the period from 2018 to the current date.
- The number of items sold during specific periods and assesses the current availability within the existing stock.
- The number of items sold for each store, considering the company's operations across multiple countries such as Germany, France, Switzerland, etc.
- The correlation between the time of the year and the performance of different product types, providing insights into seasonal trends.
- Discovers top-performing products, enabling the company to place orders in advance and avoid stockouts before the new inventory arrives.
- Identification of product managers contributing the most significant revenue, helping to recognize key contributors to the company's financial success.

For detailed findings and visualizations, please refer to the Power BI file.

## Contributing
Contributions to this project are welcome. If you would like to contribute, please follow these steps:
