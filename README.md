# E-Commerce Sales Analysis

## Overview
This project analyzes sales data from an athletic footwear company for the years 2020 and 2021. The goal of this analysis is to identify key insights related to regional and retailer performance, focusing on sales metrics, product popularity, and trends specific to women's athletic footwear.

The analysis leverages Python's Pandas library to clean and combine datasets, perform groupby operations, generate pivot tables, and resample time-series data. The data is explored to answer business-critical questions regarding sales performance by region, retailer, and product category.

## Key Findings

### 1. **Region with the Most Product Sales**
- The region with the highest number of products sold was South and Southeast regions, with 216 products sold.
- The top-performing state  within this region were Arkansas, Virginia, Texas, Tenessee, and OKlahoma 

### 2. **Region with the Most Sales Revenue**
- The region that generated the highest total sales was Northeast, with total revenue of $39,801,235.
- The top-performing state and city within this region were New York, New York 

### 3. **Top Retailer by Sales**
- The retailer that generated the highest total sales was West Gear with a total revenue of $32,794,405.
- This retailer was located in San Fransisco, California.

### 4. **Women's Athletic Footwear Sales**
- The retailer that sold the most women's athletic footwear was West Gear, with 12,107 units sold.
- The region, state, and city that contributed the most to these sales were San Fransisco, California.

### 5. **Day and Week with the Most Women's Athletic Footwear Sales**
- The day with the highest sales for women's athletic footwear was 07/16/2021, generating $12,261,098.
- The week with the highest sales was the week starting 07/11/2021, with total sales of $26271380.

## Methods Used
- **Data Combination:** The 2020 and 2021 datasets were combined using Pandas, and the date column was converted to a datetime format.
- **Groupby and Pivot Tables:** Sales data was analyzed by region, state, city, and retailer using groupby and pivot tables to aggregate sales figures and units sold.
- **Time-Series Analysis:** Daily and weekly sales trends for women's athletic footwear were analyzed using the `resample` function to identify peak sales periods.

## Tools and Libraries
- **Pandas**: Used for data manipulation and analysis.
- **Matplotlib/Seaborn (Optional)**: Used for data visualization (if any visualizations were created).
- **Jupyter Notebook**: Used for writing and running the analysis code.

## Conclusion
This analysis provides insights into the regions, retailers, and products that performed the best in terms of sales and revenue over the period of 2020-2021. The findings can help the company strategize future marketing campaigns, optimize supply chain management, and tailor promotions to the most profitable regions and products.

