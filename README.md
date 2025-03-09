# Sales Analysis Report

## Overview

This repository contains a comprehensive sales analysis conducted using Power BI and Canva for UI/UX design. The analysis aims to identify sales opportunities, optimize inventory, and develop effective marketing strategies to enhance the operational efficiency of the e-store. 

Here is the link to the interactive dashboard : https://app.powerbi.com/view?r=eyJrIjoiMzc1YzgzZTItM2QzYy00M2FiLTk0YzMtNzQwZTVhMDJhNmMwIiwidCI6IjAzNWEyYzY4LTc2YjQtNGViYS1hMTVhLWNiYmNhOTY4NjhjZCJ9

## Data Preparation

1. **Dataset Cleaning**: The initial step involved cleaning the dataset using Python. 
   - Renamed columns for clarity:
     - "Price Each" was changed to "Unit Price."
     - "Quantity Ordered" was changed to "Quantity Sold."
   - Engineered additional features:
     - **Sales Amount**: Calculated as \( \text{Sales Amount} = \text{Unit Price} \times \text{Quantity Sold} \).
     - Extracted information from the address to derive **State** and **City**.
     - Extracted **Time** from the **Order Date**.

## Analysis Scope

The analysis encompasses both regional and product insights, focusing on uncovering trends in sales, order patterns, and peak purchasing times.

### Key Insights

1. **Total Sales Performance**:
   - The business generated a total sales revenue of **$34 million**, with **208,812 products sold**.

2. **Top-Selling Products**:
   - The ten best-selling products, ranked by sales revenue, include:
     1. MacBook Pro laptops: Approximately **$8 million** in sales.
     2. iPhones: Contributed around **$4.7 million**.
     3. ThinkPad laptops
     4. Google phones
     5. 27-inch 4K gaming monitors
     6. 34-inch ultrawide monitors
     7. Apple AirPods headphones
     8. Flat-screen TVs
     9. Bose SoundSport headphones
     10. 27-inch FHD monitors

3. **Monthly Sales Trends**:
   - Monthly sales figures reveal fluctuations throughout the year, with a general upward trend:
     - **Peak Sales**: December at just over **$4.5 million**.
     - **Lowest Sales**: January at around **$1.8 million**.
     - Notable dip in September, suggesting seasonal influences, followed by recovery starting in October.

4. **Geographic Distribution**:
   - Orders were received from eight states: California (CA), Georgia (GA), Massachusetts (MA), Maine (ME), New York (NY), Oregon (OR), Texas (TX), and Washington (WA).
   - **California** emerged as the leading state, contributing **$13,717,284.10 (39.8%)** of total sales, while **Maine** contributed the least at **$448,051.99 (1.3%)**.

5. **Hourly Sales Patterns**:
   - Sales steadily rise from **6 AM**, peaking between **10 AM and 7 PM**. 
   - Analysis indicates that lower unit prices correlate with higher sales volumes and quantities sold.

6. **In-Demand Products**:
   - The top five most in-demand products include:
     - AAA batteries (4-pack)
     - AA batteries (4-pack)
     - USB charging cables
     - Lightning charging cables
     - Wired headphones
   - These products are purchased in high volumes due to their lower prices.

## Recommendations

1. **Targeted Marketing Initiatives**: Implement marketing campaigns in states and cities with lower sales performance to stimulate demand.

2. **Seasonal Product Offerings**: Introduce seasonal products, such as heaters during winter months, to align with customer needs.

3. **Peak Hour Advertising**: Increase advertising efforts during peak web traffic hours (10 AM - 7 PM) to maximize reach and engagement.

4. **Inventory Optimization**: Optimize inventory management to ensure adequate stock levels of high-demand products, minimizing the risk of stockouts and lost sales opportunities.

## Conclusion

This analysis provides valuable insights into sales performance, customer behavior, and market opportunities. By implementing the recommended strategies, the e-store can enhance its operational efficiency and drive further growth.
