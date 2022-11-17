# Bike_Sales_Analysis

## Overview of the project

We are using excel to analyze the bike sales data. Use different functions to clean up and organize data. Then create interactive dashboards to demonstrate the sales data with filters.

### Clean up and organize the data

The spreadsheet looks like this:
![spreadsheet](https://github.com/Shuchihsu/Bike_sale_analysis/blob/main/Resources/peak2022-11-17%20121448.png) 
* Clean up: Use **Remove Duplicate** and **ISBLANK** to filter and remove rows we don�t need.
* Change variable names to make sense to stakeholder: use **Replace all** for F to Female and M to Male. M to Married and S to Single.
* Create Age column to create three brackets: use IF function

**=IF(L2>54,"Old", IF(L2>=31,"Middle age�,IF(L2<31,"Adlescent","Invalid")))**

### Create graphs

Use Pivot table to create the graphs

* First graph: show how gender (Female and male) and income impact the bike sales.
![gender]( https://github.com/Shuchihsu/Bike_sale_analysis/blob/main/Resources/gender%202022-11-17%20140739.png)

* Second graph: how age groups impact bike sales.
![Age](https://github.com/Shuchihsu/Bike_sale_analysis/blob/main/Resources/age%20group%202022-11-17%20140914.png)
* Third graph: how commute distance impact bike sales.
![commute]( https://github.com/Shuchihsu/Bike_sale_analysis/blob/main/Resources/commute%202022-11-17%20140832.png)



### Create Dashboard





