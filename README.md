# Sales Analysis of an International Company

## Task

Analyze sales data of an international company (2010–2017) to find out which product categories, countries, regions and sales channels bring the most revenue and profit, how fast orders are shipped and how sales change over time.

## What the analysis does

- Cleans the data: handles missing values, converts dates, fixes inconsistent categories and checks for anomalies
- Merges three tables (orders, countries, products) into one dataset
- Calculates key metrics: revenue, cost, profit and margin
- Compares results by product category, country, region and sales channel
- Analyzes shipping time and its relationship with profit
- Shows sales dynamics by year, weekday and quarter

## Python techniques used

Pandas (`merge`, `groupby`, `pivot_table`, `melt`), datetime conversion, missing values handling, correlation analysis, data visualization with Matplotlib and Seaborn (bar charts, boxplots, heatmaps, line charts, scatter plots)

## Key findings

- The company is profitable: about 30% of revenue stays as profit
- Europe brings about 94% of revenue, Asia only 5–7%
- Cosmetics brings the most profit, while Meat and Office Supplies have the lowest margins
- Online and offline channels are almost equal in revenue and profit
- Shipping time has practically no relationship with profit (correlation ≈ 0.06)
