# E-commerce-Shipping-Data

## Table of Contents

- [Project overview](#project-overview)
- [Data Source](#Data-source)
- [Recommendations](#Recommendations)

### Project Overview

This project investigates the impact of various shipment modes (Ship, Flight, Road) on delivery timeliness within an e-commerce dataset. By leveraging SQL for data analysis, I identified trends and performance metrics for each shipping method. 

The findings provide actionable insights to optimize logistics, reduce delays, and improve customer satisfaction. This project highlights my ability to clean, analyze, and interpret real-world data to support strategic decision-making


### Data Source 

E-Commerce Shipping Data: The primary Data set used for this analysis is the "Train.csv", file, containing information about the E-commerce shipping orders from Kaggle.com.

## Tools
- Excel- Data cleaning
- SQL - Data Analysis


### Data Cleaning/Preperation

In the initial data preperation phase, I performed the following taks:
1. Data loading and inspection
2. Checking for Missing Data
3. Ensured consistency in data types across all columns, converting where necessary eg. Trim, Remove duplicate, Filter
4. Identifying and Handling Outliers
   
### Exploratory Data Analysis

- What is the overall distribution of delivery modes in the dataset?
- How does the on-time delivery rate vary by shipment mode?
- Is there a relationship between the cost of the product and the chosen mode of shipment?


### Data Analysis

Included some SQL queries I deployed

SQL Query for on time delivery rate:

![SQL 1](https://github.com/user-attachments/assets/f541bb91-381a-42ca-90cd-24e363157534)


The SQL query is analyzing the delivery performance based on Mode of Shipment and is calculating several metrics related 
to the timeliness of deliveries. 


### Results Findings

The results are summarised as follows:

1. Distribution of Delivery Modes: The ship mode is the most commonly used shipment method by the business.
2. On-Time Delivery Rate: Road transport has the best on-time delivery rate at 41%, indicating it is the most reliable option for meeting delivery expectations.
3. Cost and Shipment Mode Relationship: The average shipping costs are fairly consistent across different shipment modes, with road being slightly more expensive than ship and flight. Minimum and maximum costs are nearly identical, indicating that the mode of shipment doesn't significantly affect overall costs.

These findings suggest that the company can optimize delivery performance by favoring road transport without significantly impacting shipping costs.

### Recommendations

I recommend the follwing actions: 
- Prioritize road transport: Road has the best on-time delivery rate at 41%, making it the most reliable option for timely shipments.
- Slightly higher cost: While road transport is slightly more expensive on average, the cost difference is minimal and doesn't significantly impact overall expenses.
- Strategic choice: Given the balance between cost and reliability, focusing on road transport can improve delivery performance and customer satisfaction.

### Limitations

- Contextual Factors: While the analysis identifies trends in on-time delivery, it doesn't account for external factors like regional challenges or seasonal fluctuations that might impact performance.

 Cost Range Similarity: The costs across shipment modes are quite similar, suggesting that factors not covered in this analysis, such as distance or package weight, might also play a significant role.

- Dataset Scope: The findings are based on the available data, which may not represent every aspect of the company's shipping operations. However, the insights provided offer a strong foundation for further exploration.

