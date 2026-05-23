# Superstore Sales Analysis
---
## Executive Summary:
Using Power BI, I performed both descriptive and exploratory data analysis of a retail Superstore dataset to uncover key drivers of sales and profitability across products, categories, regions, and customer segments. The data was cleaned, transformed, and modeled to ensure accuracy and usability for analysis.

Two interactive dashboards were developed: a Sales Overview Dashboard and a Product Details Dashboard, enabling a comprehensive view of business performance.

Through these dashboards, I analyzed key business questions such as sales distribution by region and state, category and sub-category profitability, top-performing products by sales and profit, and sales trends over time.

These insights helped highlight strong and weak areas of performance across the business.

## Business Problem:
A Superstore is working with a lot of sales data from different regions, products, and customer segments, but it’s not very clear what is really driving their sales and profit.

Because of that, they want to understand things like:

- Which products, categories, and sub-categories generate the highest and lowest profit
- How sales are distributed across different regions
- Which products are top-performing in terms of sales volume and profitability
- Which areas of the business need improvement

Without this kind of analysis, it’s hard for them to make good decisions about products, pricing, and stock.

## Dataset Structure and ERD (Entity Relationship Diagram)
The database structure as seen below consists of three tables: Orders, Customers and Products with a total row count of 12,649 records.
<img width="800" alt="ER diagram" src="https://github.com/user-attachments/assets/e23d68c9-9efe-4538-a072-83d861ca4d5c" />

## Insights:
Below are the sales overview and product details dashboards:
<img width="800" alt="Screenshot 2026-05-18 142516" src="https://github.com/user-attachments/assets/edfc882d-102e-4a76-8a01-096cf7d358bb" />
<img width="800" alt="Screenshot 2026-05-18 161021" src="https://github.com/user-attachments/assets/dd3b3a95-e3c0-49e3-816c-2b7b79bd44ec" />

**Overall business performance**
The business is generating solid revenue, but the profit margin is relatively moderate (~12%), meaning profitability depends heavily on product mix and cost efficiency.

**Sales Trends**
- Sales show a small drop from 2014 to 2015
- Strong growth from 2015 to 2017
- 2017 is the highest sales year (~$733K)
The company experienced recovery after 2015 and strong consistent growth afterward, indicating improving performance or better market penetration.

**Regional Performance**
  There is a clear regional imbalance. The West region is significantly outperforming the South, suggesting either stronger demand, better customers, or better product-market fit in that region.

**Sales by State**
  Revenue is not evenly distributed geographically, a small number of states drive a large share of sales.

**Product Performance**
  High sales products are mostly technology, while high quantity products are mostly office supplies. This shows a clear split between:
high volume / low value products and low volume / high value products.

**Category performance**
  Furniture is significantly underperforming compared to the other categories, contributing only a small portion of overall profit.

**Profit Concentration**
  Top 5 products by profit are dominated by Copiers (especially Canon imageCLASS 2200)
A small number of products drive a large share of total profit which means strong dependency on a few high-performing items.

## Recommendations:
Based on the uncovered insights, the following recommendations have been provided:

**Focus on the high profit products:** Ensure availability and visibility of top-performing products as they contribute the majority of sales and profit
**Reduce dependency on top products:** Profit is concentrated in a few products (especially Copiers) and there is a risk: if top products decline then the overall profit drops significantly
**Improve Furniture category performance:** Furniture contributes only 6.4%. Investigate pricing, demand, or product mix in this category to understand why it generates lower profit compared to others
**Optimize inventory and marketing efforts based on regional performance:** South is the weakest region (~$402K sales). Investigate: customer reach, product availability, regional demand differences
**Maintain strong growth trend:** Sales are increasing strongly after 2015. Continue focusing on growth strategies that worked post-2015 (expansion, marketing, product optimization)
