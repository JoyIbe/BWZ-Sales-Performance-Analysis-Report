# BWZ-Sales-Performance-Analysis-Report
## Sales Performance & Delivery Efficiency Report

## Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Tool and Methodology](#tools-and-methodology)
- [Dashboard](#dashboard)
- [Key Analysis Findings](#key-analysis-findings)
- [Insights from Analysis](#insights-from-analysis)
- [Business Questions and Answers](#business-questions-and-answers)
- [Recommendations](#recommendations)
- [Implementation Plan](#implementation-plan)
- [Link to Viz](#link-to-viz)
- [Conclusion ](#conclusion)

## Overview
BWZ is a retail business operating across three primary product categories: Furniture, Office Supplies, and Technology. The company has generated $2.30M in total sales, with a profit margin of 46.7% and a return rate of 5.91%. This report analyzes sales performance, profitability, and operational trends to identify opportunities for growth and efficiency.

## Problem Statement
Key challenges faced by BWZ include:

- Managing profit margins amid rising costs and identifying low-profitable product category.

- Addressing return rates (5.91%) to minimize losses.

- Optimizing category-specific strategies (Furniture, Office Supplies, Technology) to maximize revenue.
  
- Investigating delivery and shipping mode bottlenecks.

- Uncovering loyal customers and most efficient sales rep persons.

## Tools and Methodology

### Tools:
Power BI: Dashboard creation and visualization.

DAX: Calculated measures for metrics like profit and return rate.

Power Query: Data cleaning and preliminary analysis.

### Method:

Data Cleaning: I carried out major cleaning steps like standardization, removing duplicates, and ensuring accuracy in the provided dataset. I also ensured a backup documentation of cleaning steps.
 
Data Processing: With Power Bi's Dax functionalities, I created calculated measures to show valuable metrics, customized and design visuals to aid clarity in understanding trends.

Data Modeling: Upon breaking the dataset to a more manageable set of dimensional tables, I defined the relationship between dimension tables and the fact table. Modeling this data allows for multiple tables with lesser column information to speed up processing time, reduce redundancy and increase efficiency.

Data Visualization: Built a three page interactive dashboards that answers stakeholders qustions in detail.

## Dashboard
The BWZ dashboard highlights:

### Sales Performance Overview Page

<img width="572" alt="BWZ Cropped" src="https://github.com/user-attachments/assets/ecb74b2c-a93f-429f-977c-6ff85cbe3998" />

### Delivery/Shipping Mode Performance Page

<img width="586" alt="BWZ 2 Cropped" src="https://github.com/user-attachments/assets/6de0afb3-66b9-4a93-8faa-919f3e9ca11d" />

### Sales Reps and Customer Performance Page

<img width="586" alt="BWZ 3 Cropped" src="https://github.com/user-attachments/assets/cf4873ff-3c20-416e-9e53-3b518030de57" />

## Key Analysis Findings

**Sales Performance:**

- While Technology category gains more sales of about 36.4% across all months especially in March,and drives higher profitability in a 41.59% mark, office supplies category follows closely at 40.47% especialy in the month of September and November and has significantly higher return rate especially in November. Furniture lags drastically in profit.
- Technology has the lowest cumulation of total quantity of 18.32% yet drives the highest business metrics, then Office Supplies has 60.48% and Futniture comes at 21.2%. This indicates the presence of premium products and buyers, which drives success metrics.

- Consumer customer segment tops across key metrics. From having a large increase gap in total sales of 50.56%, to a cummulation of 49.5% in profits and over 52% in returns

**Returns:**

- There is an overall Return rate of 5.91% indicates potential quality or fulfillment issues, especially in office supplies at 46.47% and Furniture following closely at 27.59%. Technology records the lowest value of return rate.
  
- Consumer customer segment has the highest return rate of 52.03%, Corporate follows at 31.42% and lastly Home Office records the lowest.
  
**Trends:**

Unique orders shows a steady increase from times series trend (YoY +50.8%), suggesting quality customer retention.

## Insights from Analysis

- Furniture actegory and consumer segment records the highest number of losses.

- There is a close relationship between total cost and total sales.

- Standard Class ship mode takes the longest days on average to deliver customers goods.

- All categories share a close range on the average days it takes to deliver products to customers.

- Ship mode indicates a high number of delivery that takes more than 15 days to get the customers this could be a major reason for return rates. Following closely is a good number of 3-5 days and same day delivery which also shows an efficient delivery system.
  
- There is more return rate from Office Supplies via Standard Class ship mode.

- While the West region in the US makes the highest sales, East holds the highest record of Profit. States like Califoria in the west region has the highest profit of over 80k+ while New York follows close at 79k+.

- Anna Andreadi leads in total unique orders and most quantity sold across product category and customer segment. However, Chuk Magae drives major sales and the highest number of profits in the product category, while Anna also follows closely in the product category. Other top performing sales person includes kelly williams and Cassandra Brandow who has the least performance.
  
- Sean Miller makes the highest purchase hence having the highest number of sales but genrates the lowest profits. However BWZ makes more profit off Tamara Chand and Raymond Buch who also follow Sean Miller closely. 
  
## Business Questions and Answers

**1.Which category is most profitable?**

Technology (41.59% profit).

**2. What drives the high return rate?**

Likely Furniture (lower profit margins suggest quality or logistics issues).

**3. How can BWZ improve unique orders?**

Target Corporate segments with bundled offers or loyalty programs.

**4. Why is Office Supplies less profitable despite high sales?**

It comes closely after Technology at 40.47%. This could likely be due to high return rates.

**5. How does each shipping mode (Same Day, First Class, Second Class, Standard Class) perform in terms of order volume, sales, and cost?**

Large volume of orders have above 15 days delivery days eg over 60 days delivery days. For a business that operates only in the US this raises an alarm and needs urgent intervention. 

**6. How long does it take to deliver products by category (Furniture, Office Supplies, Technology)?**

Fastest: Furniture (34.37 days).

Slowest: Technology (35.08 days).

**7. Which shipping modes struggle with on-time delivery, and where do delays occur most?**

Standard Class struggles with on-time delivery. Eg: 1,029 orders took 1-2 days; 918 took aboev 16 days (inconsistency). 



## Recommendations

- Expand marketing for high-margin Technology products.

- Reduce Returns; Improve quality control for Furniture and streamline return processes.

- Optimize Standard Class Logistics; Investigate bottlenecks and optimize delivery system.

- Consider alternative carriers or regional warehouses to speed up fulfillment.

- Increase Profitability of Same Day Delivery and monitor delayed delivery for Same Day orders to prevent customer dissatisfaction.

- Develop retention strategies for high-value customer segments.
  
- Encourage annual incentives for top performing sales person.


## Link to Viz
[Power BI Viz](https://app.powerbi.com/reportEmbed?reportId=cff8a811-b872-4181-9c84-f9f4a7538c9c&autoAuth=true&ctid=0801c8b7-f6a9-44a2-8891-282fd58fab33)

## Conclusion
The findings indicate that BWZ possesses substantial opportunities to optimize its operations. By focusing on high-margin Technology products, improving fulfillment processes for Furniture, and addressing delivery inefficiencies, the company can enhance both profitability and customer satisfaction. The exceptional performance of sales representatives like Anna Andreadi and Chuk Magae demonstrates the value of effective sales strategies that could be replicated across the team.
