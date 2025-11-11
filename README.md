# Regional Sales Analysis

![Sales Analysis](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.salesforce.com%2Fin%2Fblog%2Fsales-analysis%2F&psig=AOvVaw0Uz0fDAEnLX1ZuQQkhVUkY&ust=1762959296234000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCLDfy6Ct6pADFQAAAAAdAAAAABAE)


A Python notebook solution for comprehensive sales analytics on Acme Co.'s data (2021–2025), focusing on revenue, profit drivers, channel and regional trends, seasonality, and alignment versus fiscal budgets. The analysis enables actionable insights for pricing, promotions, and market expansion to optimize sustainable growth and reduce risk concentration.

## Project Overview

This project analyzes Acme Co.'s historical sales data to:
- Identify revenue and profit leaders across products, sales channels, and geographic regions.
- Detect seasonal trends, patterns, and outliers.
- Benchmark actual performance against planned budgets.
- Deliver insights for strategic pricing, targeted promotions, and market expansion.

## Notebook Structure

1. **Problem Statement:** Outlines the business questions and analysis goals.
2. **Importing Libraries:** Uses pandas, NumPy, matplotlib, and seaborn for efficient data manipulation and visualization.
3. **Data Import:** Loads multiple sheets from the `Regional Sales Dataset new.xlsx` source, including:
    - Sales Orders
    - Customers
    - Products
    - State Regions
    - 2024 Budgets
    - Regions
4. **Preprocessing:** Cleans and prepares dataframes for analysis; checks for missing values and redefines headers as needed.
5. **Exploratory Data Analysis (EDA):** 
    - Revenue and profit margin analysis by product.
    - Pie and bar charts aggregating performance by channel and region.
    - Distribution and histogram plots for average order value.
    - Budget comparisons and key outlier investigations.
6. **Insights & Recommendations:** Delivers actionable business findings and potential next steps.
7. **Saving Outputs:** Processed results/dataframes saved for future use or integration.

## Data Sources

- **Regional Sales Dataset new.xlsx**: The core, multi-sheet dataset containing transactional sales, master customer/product data, budget forecasts, and region/state mappings.

## Key Results & Visualizations

- **Product Profitability:** Products 18, 28, 5, and 11 lead with the highest average profit margins; recommendations for margin optimization are suggested.
- **Channel Analysis:** Wholesale comprises 54%, Distributors 31%, and Export 15% of total sales, highlighting domestic channel dominance but also opportunities in export growth.
- **Regional Performance:** 
    - West: Top sales region (~35%)
    - South & Midwest: Each >32%
    - Northeast: ~20%, representing potential for focused growth
- **Seasonal & Order Insights**: Histogram and distribution plots reveal spending levels and seasonal sales peaks/outliers.

## Visualizations

- Pie charts (Sales by Channel)
- Bar charts (Profit by Product, Regional Sales Volumes)
- Histograms (Average Order Values)
- Summary tables and dataframe snapshots

## How to Run

1. Clone or download the repository.
2. Ensure all dependencies are installed:
    - Python 3.8+ 
    - pandas
    - numpy
    - matplotlib
    - seaborn
3. Place `Regional Sales Dataset new.xlsx` in the working directory.
4. Open and run each cell sequentially in a Jupyter environment:
    ```
    jupyter notebook Regional_Sales_Analysis.ipynb
    ```
5. Review plots in-line and consult the Insights section for actionable findings.

