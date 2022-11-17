# Bike_Sales_Analysis

## Overview of the project

We are using excel to analyze the bike sales data. Use different functions to clean up and organize data. Then create interactive dashboards to demonstrate the sales data with filters.

### Clean up and organize the data

The spreadsheet looks like this:
![](https://github.com/Shuchihsu/Bike_sales_Analysis/blob/main/Resources/peak2022-11-17%20121448.png)

* Clean up: Use **Remove Duplicate** and **ISBLANK** to filter and remove rows we don’t need.
* Change variable names to make sense to stakeholder: use **Replace all** for F to Female and M to Male. M to Married and S to Single.
* Create Age column to create three brackets: use IF function

=IF(L2>54,"Old", IF(L2>=31,"Middle age”,IF(L2<31,"Adlescent","Invalid")))

### Create graphs

Use Pivot table

* First graph: show how gender (Female and male) and income impact the bike sales


### Create Dashboard





