# TNMT Retail Sales Analysis
This is an Excel capstone project for my Datascience Course at UTIVA.
## Introduction
![image](https://github.com/TochukwuPhilip/Excel_Projects/assets/108484860/b05de18f-a8bd-416b-b5f3-b2f008d940d1)
>Image from Forbes website.

TNMT is a Retail Store that sells various categories of items through various channels - Distributor, in-store, online and wholesale. The Store has locations in various regiouns in the United States of America. 
## Problem Statement
The Sales Director of TNMT Retail will like to know about the following:
- i. revenue trend
- ii. products by revenue
- iii. revenue contribution (%) of the product categories
- iv. sales team by revenue
- v. states by revenue, also showing their population and median income per state

## Aim & Objective
- i. To create a dashboard with the reports and make it sliceable by: Product Category
- ii. To include a textbox to highlight the following insights:
   -  i. Which are the 2 top revenue products in January?
    - ii. Which sales team made most revenue from Decoratives in March?
    - iii. What is the relationship between revenue, population and median income of the states?

## Data Processing
The dataset is an excel workbook that contains four(4) sheets named "Sales table", "Sales Team", "Products" and "Store Locations"
The Sales table has columns such as Order Number, Sales Date,	Sales Channel,	Currency,	Salesteamindex,	Storeindex,	Productindex,	Order qty,	unit price,	unit cost.
The Sales Team sheet has columns such as Index,	Sales Team, and	Region.
The Products sheet has columns such as Index,	Product Name, and Product Category.
The Store Locations sheet has columns such as id,	name,	county,	state_code,	state,	type,	latitude,	longitude,	area_code,	population,	households,	median_income,	land_area,	water_area	and time_zone

## Data Modeling
I have utilized PowerPivot add-in to build the data model for this project.

<img width="812" alt="image" src="https://github.com/TochukwuPhilip/Excel_Projects/assets/108484860/2a46b851-e57c-402a-94f8-a3a76d419c3a">

The different tables were connected using primary keys and secondary keys.
There is a many-to-one relationship between the Sales table and the other three tables using "Salesteamindex", "Storeindex", and "Productindex" as unique identifiers

## Data Analysis
<img width="593" alt="image" src="https://github.com/TochukwuPhilip/Excel_Projects/assets/108484860/6e334c31-edbe-4658-8594-94159469be40">

The various charts have been created.
To allow for interactivity among the tables, the Slicer tools have been used. This allows for indepth analysis of the TNMT sales for different product categories and different periods.


## Share
### INSIGHTS
- REVENUE TREND:
The highest resvenues are made in May and January while the lowest revenues are made in February and April

- TOP REVENUE PRODUCTS: The product with the highest sum of revenue is Clock. While the top producst for January are Vanities and Collectibles

- SALES TEAM REVENUE:
Nicholas Cunningham makes the highest revenue sum. Patrick Graham Team makes the least sum of revenue.
Donald Reynolds Team makes the most revenue from Decoratives in March.

- RELATIONSHIP BETWEEN REVENUE POPULATION AND MEDIAN INCOME:
From the combo chart above, one can see that there is a positive relationship among the three variables - the higher the population, the higher the revenue and median income.



 

