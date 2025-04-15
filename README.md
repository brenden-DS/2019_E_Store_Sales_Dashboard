# Sales Analysis Report

### Overview/Context:
This project conducts a comprehensive sales analysis for an e-store, focusing on identifying sales opportunities, optimizing inventory, and developing effective marketing strategies to enhance operational efficiency. The analysis was fully performed in Power BI, with Canva used for UI/UX design of the dashboard. An interactive Power BI dashboard was created to present the findings
 [Link](https://app.powerbi.com/view?r=eyJrIjoiMzc1YzgzZTItM2QzYy00M2FiLTk0YzMtNzQwZTVhMDJhNmMwIiwidCI6IjAzNWEyYzY4LTc2YjQtNGViYS1hMTVhLWNiYmNhOTY4NjhjZCJ9)

### Dataset

- The dataset includes e-store transaction records with features such as Order Date, Price Each, Quantity Ordered, Address, and product details. It covers sales activities across eight states in 2019, with total sales of $34 million and 208,812 products sold.

### Data Preprocessing:
- Data cleaning was initially performed using Python’s pandas library, followed by further processing in Power BI’s Power Query. Steps included:  
 Renaming columns for clarity: “Price Each” to “Unit Price” and “Quantity Ordered” to “Quantity Sold.”  

- Handling missing values, removing duplicates, and standardizing date formats to ensure data consistency.

### Business Questions:  
- What are the total sales and products sold in 2019?  

- Which products are top-selling and most in-demand, and what are their sales contributions?  

- How do sales vary by month, hour, and geographic location?  

- What are the peak purchasing times, and how do unit prices impact sales volumes?  

- How can the e-store optimize operations and marketing to drive growth?


### Visuals

Overview

![Overview](https://github.com/brenden-DS/2019_E_Store_Sales_Dashboard/blob/main/overview%202019.PNG)

Sales

![Sales](https://github.com/brenden-DS/2019_E_Store_Sales_Dashboard/blob/main/product%202019.PNG)

Records

![Records](https://github.com/brenden-DS/2019_E_Store_Sales_Dashboard/blob/main/records%202019.PNG)

### Key Insights

- Sales Overview: The e-store generated $34 million in revenue, selling 208,812 products.  

- Top-Selling Products: MacBook Pro laptops led with $8 million, followed by iPhones at $4.7 million; other top products include ThinkPad laptops and Google phones.  

- In-Demand Products: High-volume, low-price items like AAA batteries, USB charging cables, and wired headphones topped demand.  

- Monthly Trends: Sales peaked in December at $4.5 million and dipped in January at $1.8 million, with a notable decline in September.  

- Geographic Performance: California contributed 39.8% of sales ($13.7 million), while Maine lagged at 1.3% ($448K).  

- Hourly Patterns: Sales rose from 6 AM, peaking between 10 AM and 7 PM, with lower unit prices correlating with higher sales volumes.

### Recommendations:  
- Targeted Marketing: Launch campaigns in low-performing states like Maine to boost demand.  

- Seasonal Offerings: Introduce seasonal products (e.g., heaters in winter) to align with customer needs and address monthly dips.  

- Peak Hour Focus: Increase advertising during peak hours (10 AM–7 PM) to maximize engagement.  

- Inventory Management: Ensure adequate stock of high-demand products like batteries and cables to prevent stockouts and lost sales.

### Conclusion:
- This Power BI analysis reveals key sales trends, with California and high-demand products driving performance, while identifying opportunities in underperforming regions and time periods. The interactive 
 dashboard provides an accessible overview for stakeholders, offering a clear path to optimize operations and drive e-store growth.

