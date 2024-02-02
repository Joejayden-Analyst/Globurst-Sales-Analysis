### Globurst-Sales-Analysis

## Overview

Globurst is a superstore in Lagos Nigeria, a single branch supermarket. Unlike other chain stores, Globurst attempt to embrace data driven approach for its growth and market domiance based on recent trends.

This data covered a period of two years 2021 to 2022. During this period, the we examine the growth in term of revenue generated and sales made in the period in consideration. 

## Problem Statements
This following are the problem statements:
- The top 15 revenue generating products
- The monthly sales trend during the period
- The top sales based on categories.
- The sales made from the diffrent sales channels
- The order of Payment methods used.
- Profut made on quarterly basis.

## Skills demonstrated
The following skills were demonstrated during this analysis;
- Data cleaning  and transformation.
- Data normalization and Data modellng.
- Dax calculation for measures and conditional formating.
- Data Vitalization.
- Analytical, Predictive and critical skills.

## Data source

This is a computer generated data by the POS system, printed out from the system into an excel file named "input data". This data has 528 rows and 16 fields. It is a clean data having zero errors and has no null values. 

## Data Transformation

i decided to normalize my data due to its numerous advantages especially for removing reduntant data and duplicated values which will consequently lead to faster queries or laoding as the case may be. The input data was renamed to sales data then duplicated into and renamed products. Irrelevant fields not relating to products was removed, then i removed duplicates from the remaning products data.Thereafter, a date table was created using the calender function. Therefore we have three datasets, sales data , products and date.

## Data Modelling

Relationships were detected automatically among the three tables, using star schema. The sales table being the fact table and date and products being dimension table. One to many relation was established bwtween the products and the sale data using the product key as the link, also the date table was liked to the sales data using the filed coloumn date as the primary key.

## Analysis And virtualization
The following are the insights;

# Revenue Generated from sales

the revenue generated from sales was above #118000.00k

#  The Profit
The Profit at the period was #115000.27k

# The profit Margin
The proft margin was 18.65%

#  Quantity Sold 
The total quantity sold was 4280 units

# Top 15 revenue generating Products
The top product is Sonny Bravia Full HD 1080 followed by Samsung Smartwatch and Toshiba 43" televison made the top three why the last three rvenue generating products are; Mackerel, Halibut and Bat Music 5800. The full top 15 products  are shoen below.

# Top used sales channel
More sales and revenue were made from direct sales which account to about 50.9% of the total sales, followed by online sales which account to 34.4% and lastly sales made by wholesalers account to 14.7% of the total revenue.

# Top Payment method
over half of the sales was recieved by cash(#414000.37k), which is probably due to high  direct sales and a whopping amount of #393000.79k was made from online sales.

# The Monthly Sales Trend
The sales trend shows that most sales are on January, then July and June repectively.

# Top Sales By Category
The highest revenue was made from electronic related appliances, gloceries and Home office.
respectively.

# Sales By Quarters 3142
Most sales was made in the 3rd quarter, 1st quarter, 4thquarter and 2nd quarter repectively.

## Conclusion, Recomenations and Predictions.

