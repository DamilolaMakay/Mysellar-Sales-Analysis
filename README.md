# Mysellar Global Sales Analysis

## Introduction
This project involves an in-depth analysis of the global sales data for Mysellar, a multinational retail corporation operating both online and offline. The goal of this analysis is to provide key insights that can guide Mysellar’s decision-making, specifically focusing on identifying profitable products and regions to concentrate sales efforts.

The data analyzed covers various regions, countries, and product categories, with key metrics such as units sold, total revenue, total cost, and shipping time.

## Objectives

- To assess the total yearly profit across Mysellar’s online and offline sales channels.
- To analyze sales performance by region and product category.
- To evaluate shipping times and identify regions with the fastest and slowest delivery.
- To determine if there is a correlation between sales and economic productivity, specifically for Sub-Saharan African countries.

## Tools

- Power BI: For data cleaning, transformation, and visual analysis.
- Power Query: To merge and clean data from different sources.
- DAX (Data Analysis Expressions): To create custom measures for analyzing profitability, sales trends, and shipping times.
-GitHub: For version control and sharing the project.

## Techniques and Skills

- Data Transformation: Using Power Query to merge sales data from different sources and ensure consistency.
- DAX Calculations: Creating custom measures for metrics such as profit margins, average shipping time, and correlation analysis.
- Time Intelligence: Leveraging Power BI’s Date Hierarchy to analyze trends across various time frames, including yearly and monthly trends.
- Visual Analysis: Scatter plots, matrix visuals, and bar charts to present key findings on sales performance and region-specific insights.
- Correlation Analysis: Investigating the relationship between sales and GDP for Sub-Saharan African countries to provide strategic insights on potential markets.

## Data Source

Sales Data: Mysellar’s historical sales data across various categories, regions, and sales channels.
GDP Data: External economic data for Sub-Saharan African countries, integrated into the analysis to explore correlations with sales performance.

## Data Model

Fact Table: The sales data containing fields such as Order Date, Country, Category, Units Sold, Total Revenue, Total Cost, and Sales Channel.
Date Table: Generated using Power BI’s built-in Date Hierarchy, facilitating trend analysis over time.
Lookup Table: A separate GDP data table, which was merged with the sales data by country to enable correlation analysis.

## Dashboard Insights

The dashboard showcases yearly profits by sales channel, highlighting Online and Offline performance. Europe emerged as the region with the highest units sold, while North America showed the lowest.
Average shipping times were shortest in Europe and North America, while Australia & Oceania and Asia had the longest shipping times.

## Correlation Between GDP and Total Sales in Sub-Saharan Africa

A slight downward trend was observed between GDP and total sales, suggesting a weak correlation.
Noteworthy observations: Equatorial Guinea, Comoros, and Somalia had high sales but lower GDP, while Algeria and South Africa displayed a balanced relationship between sales and GDP.

## Recommandations

- Target Market Expansion: Regions with high GDP but lower sales, such as Nigeria and Egypt, present opportunities for Mysellar to invest in improving marketing efforts or expanding product lines.
- Optimize Shipping Logistics: Efforts to reduce shipping times in Australia & Oceania and Asia could improve customer satisfaction and sales volumes in those regions.
- Profit Maximization Strategy: Focusing on high-profit regions like Sub-Saharan Africa and Europe, while optimizing costs in low-profit regions, could improve overall profitability.

## Download
