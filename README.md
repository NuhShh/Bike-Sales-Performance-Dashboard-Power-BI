![Logo](pbi/Logo.png)

<div align="center">

# Sales Performance & Product Profitability Analysis for Velox Cycles Europe

</div>

## Executive Summary

Velox Cycles Europe, a premium bicycle retailer operating across multiple European markets, needed to understand where profit opportunities are being missed. The analysis revealed two critical findings. First, revenue is dangerously concentrated in just two markets (the US and Australia), creating significant business risk. Second, while bikes drive €62M in revenue, high-margin accessories (60-72% margin) contribute only €15M because cross-sell strategies are underutilized. By implementing bundle offers and expanding into untapped European markets, Velox Cycles can improve both revenue diversification and overall profitability without requiring additional customer acquisition.

Metrics:
1. **Geographic Performance** – Revenue concentration across markets
2. **Product Profitability** – Revenue vs. margin by category
3. **Efficiency Benchmarks** – High-margin items driving profit


### Business Problem

Velox Cycles relies on product sales for revenue, but stakeholders want to identify where profit is being maximized versus where opportunities are being missed. The challenge is twofold: revenue is over-concentrated in a small number of markets, and high-margin products are not being adequately promoted to customers purchasing main products. This analysis directly addresses these profitability gaps by examining geographic distribution and product category performance.


## Results & Business Recommendations

### 1. Revenue Over-Reliance on Two Markets

![Page 1 - Sales Overview](pbi/Sales%20Overview%20Dashboard_page-0001.jpg)

The analysis of €85.27M in total revenue revealed that 58% comes from just two markets: the United States (€27.98M) and Australia (€21.30M). This creates significant business risk. If either market declines, the entire business suffers. Meanwhile, key European markets where Velox Cycles already operates (Germany, UK, France, and Canada) all remain under €11M each, representing substantial untapped potential. The marketing team should prioritize European market expansion to reduce geographic dependency.


### 2. High-Margin Accessories Are Severely Underutilized

![Page 2 - Product Analysis](pbi/Sales%20Overview%20Dashboard_page-0002.jpg)

To understand true profitability, the analysis broke down performance by product category. While bikes generate €61.78M in revenue (the primary revenue engine), accessories contribute only €15.12M despite featuring the highest margins in the entire portfolio. Items like the Road Tire Tube (72.49% margin), Road Bottle Cage (62.84% margin), and Racing Socks (63.2% margin) dramatically outperform bikes in profitability. The critical insight: customers purchasing high-ticket bikes are not being guided toward high-margin accessories at the point of sale. Every bike sale should trigger an accessory cross-sell recommendation. This represents a massive profit opportunity being left on the table.


### Recommendations

Based on the data, here are the recommended actions:

1. **Implement Margin-Boosting Bundles**: The sales team should create bundle offers that pair bikes with high-margin accessories to capture 60-72% margin uplift on every bike sale.

2. **Expand European Markets**: The marketing team should increase advertising spend in Germany, UK, France, and Canada to reduce geographic dependency on US and Australia.

3. **Ensure Hero Product Availability**: The operations team should guarantee 100% stock availability for top-selling products like the Road-150 Red series, as these drive customer traffic.


### Next Steps

1. Develop bundle pricing strategy for bike + accessory combinations
2. Create targeted marketing campaigns for European market expansion
3. Implement inventory early-warning system for hero products
4. Establish monthly profit margin tracking dashboard


### Methodology

1. **Data Preparation**: Extracted and validated sales data from the European bike sales dataset. Created a custom Date Table for time-based analysis and built a structured star schema with fact and dimension tables.

2. **Data Modeling**: Developed key DAX measures including Total Revenue, Total Profit, Profit Margin, and Total Quantity. Implemented time-based analysis and Top N filtering.

3. **Dashboard Design**: Built a multi-page interactive dashboard featuring KPI cards, trend lines, geographic maps, and detailed breakdowns by product category.

4. **Scope**: Analyzed data from January 2011 through July 2016 to ensure comprehensive trend analysis.