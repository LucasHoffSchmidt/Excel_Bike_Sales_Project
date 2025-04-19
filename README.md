# Excel Bike Sales Project
In this project we used Excel to analyse bike sales data, to determine the customers most likely to buy a bike. 

## Quick Links
- Bike buyers dataset: [Bike Buyers Dataset](bike_buyers_dataset.xlsx)
- Final dashboard of bike sales: [Bike Sales Dashboard](bike_sales_dashboard.png)
- Bike sales excel project file: [Excel Project File](bike_sales_project.xlsx)
- Other projects I have made: [Portfolio Website](https://lucashoffschmidt.github.io/)

## Tools Used
- **Excel**: Data cleaning, data exploration and creation of final dashboard.

## Project Objective
- Identify primary customers of bikes.

## Data Source
- [Bike Buyers Dataset](bike_buyers_dataset.xlsx)

## Process
- **Data Cleaning**:
  - Opened the excel dataset of bike buyers.   
  - Made sheets for cleaning, pivot tables and dashboard.
  - Removed duplicates through data -> remove duplicates.
  - Replaced single letter values with full words using find and replace.
  - Changed format of Income column to currency and removed decimals.
  - Made age brackets using IF conditions.
- **Data Exploration and Dashboard Creation**:
  - Made a pivot table based on gender, average income and if the customer purchased a bike.
    - Made a clustered column chart from the pivot table.
    - Changed format of pivot table to numbers and removed decimals.
  - Made a pivot table based on commute distance and number of bikes bought.
    - Made a line chart from the pivot table.
    - Changed rows from 10+ Miles to More than 10 Miles.
  - Made a pivot table based on age bracket, number of bikes bought and if the customer purchased a bike.
    - Made a line chart from the pivot table.
  -  Made a bike sales dashboard with a header and the charts made from the pivot tables.
  -  Aligned the visuals to have even space between them.
  -  Made slicers on marital status, region and education.
  -  Connected each slicer to all charts through PivotTable Connections.

## Key findings
- Higher income indicates higher likelihood of buying a bike.
- The majority of customers are between 31-55 years old.
- Most customers have a commute of less than a mile.

## Final dashboard
![Bike Sales Dashboard](bike_sales_dashboard.png)

## Conclusion
The analysis indicates that the people most likely to buy a bike has one or more distinguishing characteristics: higher income, being between 31-55 years old and having a commute of less than a mile. 
