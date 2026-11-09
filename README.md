# Global-Electronics-Retailer
# Global Electronics Retailer Analysis

## Project Overview

This project focuses on analyzing the sales and financial performance of a fictional global electronics retailer. The main objective was to understand how the company's revenue changed over time, identify areas of strong and weak performance, and investigate patterns that could help management make better business decisions.

Rather than focusing only on total sales, I wanted to look at the business from different angles, including product categories, customer activity, regional performance, profitability, and individual store performance.

## Tools Used

1. Power BI
2. DAX
3. Power Query

## Dataset

The dataset contains five tables covering different areas of the business:

1. Sales: Individual sales transactions and order information.
2. Products: Product information, unit prices, and unit costs.
3. Customers: Customer information.
4. Stores: Store locations and information.
5. Exchange Rates: Historical currency exchange rates.

The Sales table contains approximately 62,884 records, covering individual sales line items.

An important limitation is that the dataset only contains part of 2021, which affects comparisons involving that year.

## Data Preparation and Analysis

Before beginning the analysis, I reviewed the tables and checked for potential duplicate records.

Some of the steps included:

1. Investigating possible duplicates in the Sales table using Order Number and Product Key.
2. Checking the Products and Customers tables using their unique identifiers.
3. Reviewing repeated order and product combinations to distinguish legitimate transactions from potential duplicates.
4. Creating calculated columns for Total Revenue, Cost of Goods Sold (COGS), and Gross Profit.
5. Using the DAX RELATED function to retrieve product prices and costs from the Products table.
6. Creating measures for Gross Profit Margin and Revenue Growth.

## Business Questions

The analysis focused on six main questions:

1. How has revenue changed over time, and are there noticeable seasonal patterns?
2. Which product categories generate the most revenue, and which have the weakest growth?
3. Are customers purchasing less frequently or buying fewer products?
4. Which countries and markets are performing well or underperforming?
5. How are product costs and profitability changing over time?
6. Which individual stores are performing best and worst?

## Key Findings

### 1. Revenue Trends

Revenue generally followed a recurring seasonal pattern, with noticeable declines around April and increases toward December.

However, 2020 showed a significant decline in revenue compared with previous years. Order volume also decreased considerably.

One example was December, when the business recorded 2,411 orders in 2020 compared with 9,343 in December 2019.

### 2. Product Performance

Computers generated the highest total revenue at approximately $19.30 million.

Cell phones were another interesting category. They reached the second highest position in revenue and recorded the highest revenue growth among product categories at 16.17%.

This suggests that cell phones became an increasingly important part of the retailer's business.

### 3. Customer Activity

Order volume and quantity sold followed patterns similar to revenue.

The decrease in orders during 2020 suggests that lower sales volume may have contributed to the decline in revenue. However, additional information would be needed to determine whether customers were purchasing less frequently or simply buying fewer products.

### 4. Regional Performance

The United States generated the highest revenue, supported by its 24 stores.

Canada also demonstrated competitive performance despite having only five stores, recording 12.24% revenue growth and a 58.26% gross profit margin.

The Netherlands showed comparatively weaker revenue growth at 9.09%.

### 5. Profitability

Gross profit margins remained relatively consistent across several markets.

COGS generally moved alongside revenue, suggesting that product costs followed similar patterns as sales activity.

However, the available information does not establish whether changes in product costs contributed significantly to the revenue decline.

### 6. Store Performance

Store performance varied considerably.

Some locations generated substantial revenue while experiencing relatively modest growth. Others generated less revenue but demonstrated stronger growth rates.

This highlighted the importance of looking at both revenue and growth when evaluating individual store performance.

## Recommendations

Based on the findings, I identified two areas that deserve further investigation:

1. Investigate the recurring April decline.

Revenue, order volume, and quantity sold all showed noticeable decreases around April. Management should investigate whether this pattern is related to seasonality, inventory availability, reporting issues, or other operational factors.

2. Investigate declining order volume.

The decrease in orders during 2020 suggests that changes in customer purchasing activity may have contributed to lower revenue. Further investigation could help determine whether customers are purchasing less frequently or buying fewer products per order.

## Limitations

There are several limitations to consider when interpreting the results.

1. The dataset only contains part of 2021, making full year comparisons difficult.
2. Some stores recorded 0% revenue growth. It is unclear whether these locations were newly opened, inactive, or missing historical transactions.
3. Some orders were not marked as delivered. The available data does not establish whether these were delivery issues, incomplete records, or products that did not require physical delivery.
4. The dataset does not provide enough information to establish the underlying cause of the recurring April decline.

## Conclusion

This project helped me develop a better understanding of how different business metrics can be used together to investigate company performance.

One of the most interesting findings was the recurring April decline in revenue and order volume. Although the data revealed several patterns, it also demonstrated the importance of recognizing data limitations and avoiding conclusions that cannot be supported by the available information.

The goal was not simply to visualize sales figures, but to investigate what those figures could tell us about the business and identify areas where further analysis could be useful.
