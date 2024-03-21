# FurniTech Solutions Sales Data Analysis

![](Intro_image_FurniTech_Solutions.jpg)
---

## Table of Contents
* [Introduction](#introduction)
    * [Company background](#company-background)
    * [Current position](#current-position)
    * [Company objectives](#company-objectives)
* [Executive summary](#executive-summary)
    * [The problem](#the-problem)
    * [The analysis's goal](#the-analysiss-goal)
    * [The data and techniques employed](#the-data-and-techniques-employed)
    * [Brief interpretation of results](#brief-interpretation-of-results)
* [Main body](#main-body)
    * [Summary of errors in data](#summary-of-errors-in-data)
    * [Additional calculations and columns](#additional-calculations-and-columns)
    * [Hypothesis](#hypothesis)
* [Analysis](#analysis)
    * [Written insights](#written-insights-explaining-the-outcomeresults-of-each-analysis-and-response-to-hypothesis)
* [Conclusion](#conclusion)
* [Recommendations for action](#recommendations-for-action)
* [Dashboard](#dashboard)

## Introduction
This is an Excel project of an **imaginary store** called **FurniTech Solutions**. Data set was provided on Youtube video description (name of the channel: Skillnator, name of the video: "Create interactive excel dashboard in 5 simple steps". The project aims to provide insights into the sales performance of the company. By analysing data we seek to identify trends and gain a deeper understanding of the company's performance.

### Company background
FurniTech Solutions operates in the retail industry, specialising in online sales of furniture, office supplies and technology.

### Current position
Despite strong sales performance, FurniTech Solutions faces challenges in analysing sales data efficiently and deriving actionable insights.

### Company objectives
The primary objectives include optimising inventory management, identifying top-performing products, and enhancing overall sales performance.

## Executive summary

### The problem
FurniTech Solutions struggles to effectively track sales trends, monitor inventory levels, and identify areas for improvement due to the complexity and volume of sales data. 

### The analysis's goal
The goal of this analysis is to analyse historical data to identify trends and petterns and to develop an interactive Excel dashboard that enables FurniTech Solutions to visualize sales data dynamically and derive actionable insights.

### The data and techniques employed
Sales data from FurniTech Solutions were collected and analysed using Excel. Techniques such as pivot tables, charts, slicers and conditional formatting were employed to create interactive visualisations.

### Brief interpretation of results
The interactive dashboard enables FurniTech Solutions to monitor sales trends and identify opportunities for growth and optimisation.

## Main body

### Summary of errors in data
The dataset was carefully reviewed for errors but no duplicate values, data inconsistencies or missing values were found.

### Additional calculations and columns
Additional calculated column was made:
- Price (Sales/Quantity).

### Hypothesis
- **Which customer segment is the best-selling and most profitable** (Understanding which customer segment contributes the most to sales and profits allows for targeted marketing efforts and tailored customer experiences. It helps in allocating resources effectively towards segments that offer the highest return on investment);
- **Which product category has the highest sales and profit** (Identifying the top-performing product categories informs inventory management, pricing strategies, and product development efforts. It guides decision-making on resource allocation and expansion opportunities in high-demand product categories);
- **Correlation between quantity sold and profit** (Analyzing the relationship between quantity sold and profit provides insights into pricing strategies, production costs, and overall profitability);
- **How discount impact sales** (Understanding the impact of discounts on sales revenue helps in designing effective promotional campaigns and pricing strategies. It informs decisions on discounting levels, timing, and target segments to achieve desired sales outcomes while maintaining profitability);
- **Which regions have the highest and lowest sales and profits** (Identifying regional sales and profit performance highlights geographic market opportunities and challenges. It guides resource allocation, market expansion strategies, and localized marketing efforts to capitalize on high-performing regions and address underperforming ones);
- **Which states and cities have the highest and lowest sales and profits** (This analysis will provide insights into the regional performance of the business and help identify areas of strength and opportunities for improvement);
- **Trend in sales and profit over time** (Monitoring sales and profit trends over time provides insights into business performance, market dynamics, and seasonality effects. It helps in forecasting future sales, identifying growth opportunities, and adjusting strategies to align with changing market conditions).

## Analysis
<p align="center" width="100%">
    <img width="40%" src="Customer_segment_by_sales2.PNG">
    <img width="40%" src="Customer_segment_by_profit1.PNG">
</p>

Based on the charts, it is evident that the Consumer segment generates the highest sales and profit, while the Home Office segment demonstrates lower performance.

<p align="center" width="100%">
    <img width="40%" src="Product_category_by_Sales1.PNG">
    <img width="40%" src="Product_category_by_Profit1.PNG">
</p>

We can see from the charts that the product category with the highest sales and profit is Technology. There is a significant disparity in profit between the Furniture product category and Office Supplies and Technology, with Office Supplies and Technology generating at least six times more profit than Furniture. Interestingly, despite this difference in profit, the sales charts indicate that Furniture actually has higher sales than Office Supplies.

<p align="center" width="100%">
    <img width="50%" src="Correlation_Quantity_Profit1.PNG">
</p>

To understand the correlation between quantity sold and profit, I conducted a correlation analysis. The results of this analysis reveal that there is no correlation between the quantity sold and profit.

<p align="center" width="100%">
    <img width="50%" src="Discount_and_Sales.PNG">
</p>
<p align="center" width="100%">
    <img width="50%" src="Correlation_Discount_and_Sales.PNG">
</p>

To understand how discounts impact sales, I created a pivot table with pivot chart and conducted a correlation analysis. As shown in the chart, there is no correlation between discount and sales. Interestingly, the highest sales were recorded with a discount of 20%. Furthermore, the correlation analysis confirms the absence of any correlation between discounts and sales. Overall, the purpose of this analysis was to investigate whether higher discounts influence sales. However, the findings suggest that discount percentage alone may not be a significant driver of sales

<p align="center" width="100%">
    <img width="40%" src="Region_by_sales1.PNG">
    <img width="40%" src="Region_by_profit1.PNG">
</p>

As observed from the charts, the West and East regions exhibit the highest sales and profits. Interestingly, although the Central region demonstrates higher sales than the South, it actually has lower profits compared to the South region.

<p align="center" width="100%">
    <img width="40%" src="States_with_highest_Sales.PNG">
    <img width="40%" src="States_with_highest_Profit.PNG">
</p>
<p align="center" width="100%">
    <img width="40%" src="States_with_lowest_Sales.PNG">
    <img width="40%" src="States_with_lowest_Profit.PNG">
</p>


<p align="center" width="100%">
    <img width="40%" src="Sum_of_Sales_by_Product_Category.png">
    <img width="40%" src="Sum_of_Profit_by_Product_Category.png">
</p>
<p align="center" width="100%">
    <img width="40%" src="Sum_of_Quantity_by_Product_Category.png">
    <img width="41%" src="Sum_of_Unit_Price_by_Product_Category.png">
</p>

The analysis of the provided charts reveals that the Technology category emerges as both the most selling and most profitable product category. Despite Office Supplies being the most ordered category, its comparatively lower average unit price results in smaller profits.
<p align="center" width="100%">
    <img width="40%" src="Sum_of_Sales_by_PSC_and_PC.png">
    <img width="40%" src="Sum_of_Profit_by_PSC_and_PC.png">
</p>

The charts above indicate that the Telephones and Communication, along with Office Machines, emerge as the most profitable sub-categories.
<p align="center" width="100%">
    <img width="40%" src="Sum_of_Sales_by_Customer_Segment.png">
    <img width="40%" src="Sum_of_Profit_by_Customer_Segment.png">
</p>
<p align="center" width="100%">
    <img width="40%" src="Sum_of_Quantity_by_Customer_Segment.png">
    <img width="40%" src="Sum_of_Unit_Price_by_Customer_Segment.png">
</p>

The analysis of the provided charts reveals that the Corporate customer segment emerges as both the most selling and most profitable. While the Consumer segment has the highest average unit price, its smaller quantity of orders results in comparatively lower sales and profit.
<p align="center" width="100%">
    <img width="40%" src="Top_10_Products_by_Sales.png">
    <img width="39%" src="Top_10_Products_by_Profit.png">
</p>

Charts above shows top products by sales and by profit.
<p align="center" width="100%">
    <img width="40%" src="Sum_of_Sales_by_Region.png">
    <img width="40%" src="Sum_of_Profit_by_Region.png">
</p>

The treemaps clearly indicate that the East region leads in terms of sales, while the West region emerges as the most profitable.
<p align="center" width="100%">
    <img width="40%" src="Average_of_Unit_Price_by_PSC_and_PC.png">
</p>

The chart above illustrates significant variability in unit prices among different product sub-categories. Notably, Copiers and Fax and Office Machines emerge as the most expensive sub-categories, indicating a clear division between more and less expensive product categories.
<p align="center" width="100%">
    <img width="40%" src="Sum_of_Sales_by_Month.png">
    <img width="40%" src="Sum_of_Profit_by_Month.png">
</p>
<p align="center" width="100%">
    <img width="40%" src="Average_of_Unit_Price_by_Month.png">
    <img width="40%" src="Sum_of_Quantity_by_Month.png">
</p>

The charts show the trends over time for sales, profit, unit price, and quantity ordered. Notably, January and March exhibit the smallest sales figures, attributed to higher unit prices and lower quantities ordered during these months. In February, a decrease in unit price, coupled with a rise in the quantity of orders, resulted in increased sales and profit. May shows the smallest average unit price and the highest quantity of orders, leading to a small increase in profit but a decline in sales.
Furthermore, the data indicates a 17.5% growth in sales during the second quarter compared to the first quarter. However, profit experienced an 18% decline during this period.

### Written insights explaining the outcome/results of each analysis and response to hypothesis
- **Correlation between order priority and date difference**: There is a correlation between order priority and date difference, particularly noticeable in low-priority orders. However, the difference in shipping time between high, critical, and medium priority orders is not significant.
- **Correlation between ship mode and date difference**: There is no correlation between ship mode and date difference, indicating that the chosen shipping method does not significantly impact the time it takes for orders to be shipped.
- **Relationship between quantity of products and discount**: There is no correlation between the quantity of products ordered and the discount offered, suggesting that discount offers do not influence the quantity of products ordered.
- **Best and worst performing product categories and customer segments**: The top-performing product category in terms of sales and profit is technology, while the underperforming category is office supplies. Similarly, the corporate customer segment performs best in both sales and profit, while the consumer segment underperforms.
- **Regions with highest sales and profits**: The region with the highest sales is the East, whereas the region with the highest profit is the West.
- **Variability in unit prices across product sub-categories**: The most expensive product sub-categories are copiers and fax, and office machines, indicating higher pricing for these items compared to others.
- **Trends in sales and profits over time**: Sales show a growth of 17.5% in the 2nd quarter compared to the 1st quarter. However, there is a notable decline in profit by 18% during the same period.

## Conclusion
The analysis highlights opportunities for Office World to focus its marketing efforts on promoting top-selling and high-profit products to its target customer segments. By understanding customer preferences and purchasing patterns, Office World can tailor its marketing campaigns to better meet customer needs and drive sales.

## Recommendations for action
Based on the analysis findings, recommendations for action include:
- Developing targeted marketing campaigns to promote top-selling products to specific customer segments;
- Expanding product offerings in high-demand categories to capitalize on market trends and customer preferences;
- Implementing pricing strategies to optimize profitability while maintaining competitive pricing;
- Investing in customer relationship management (CRM) systems to personalize marketing communications and improve customer engagement.

## Dashboard
![](Project_Office_Supply_dashboard.PNG)
---
