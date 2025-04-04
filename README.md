# Bike Sales Dashboard Project

## Project Summary

The Bike Sales Dashboard is a data analytics project built using Microsoft Excel to understand the demographics and lifestyle factors that influence a customer's decision to purchase a bike. This interactive dashboard allows users to gain insights into which groups of people are more likely to buy a bike based on factors like gender, income, commute distance, age, education, region, and marital status.

By leveraging pivot tables, slicers, and dynamic charts, the dashboard provides a comprehensive and user-friendly way to explore and analyze the sales data.

## Dataset Description

The dataset used in this project contains the following fields:

- ID  
- Marital Status (M/S)  
- Gender (M/F)  
- Income  
- Children  
- Education  
- Occupation  
- Home Owner  
- Cars  
- Commute Distance  
- Region  
- Age  
- Purchased Bike (Yes/No)

## Data Cleaning and Preparation

To ensure consistency and improve analysis, the following preprocessing steps were performed:

- Replaced 'M' and 'S' in Marital Status with 'Married' and 'Single'  
- Replaced 'M' and 'F' in Gender with 'Male' and 'Female'  
- Created a new field called Age Bracket to simplify age-based analysis:
  - Under 30  
  - 30–50  
  - Above 50  

## Dashboard Components

1. Average Income vs Gender and Purchase  
A pivot table was created to analyze the average income of males and females, based on whether they purchased a bike.  
A bar chart was used to visualize this comparison clearly.

2. Bike Purchase vs Commute Distance  
A line chart was created to compare how many people with varying commute distances have purchased or not purchased a bike.  
This reveals which commute distance range leads to higher likelihood of purchasing a bike.

3. Bike Purchase vs Age Bracket  
A pivot chart and line or bar chart were used to analyze how bike purchases vary by age bracket (under 30, 30–50, above 50).

## Interactivity

Slicers were added for:

- Region  
- Education  
- Marital Status  

These slicers are connected to all pivot tables and charts, enabling dynamic filtering and easy analysis across different demographics.

## Final Dashboard

All charts, slicers, and pivot tables were arranged and formatted into a single, visually appealing Excel Dashboard.

![Screenshot 2025-04-04 222212](https://github.com/user-attachments/assets/a9d9a7f2-6221-4269-8e58-71ae47ae0deb)
