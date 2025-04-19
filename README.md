# Excel Bike Sales Project
In this project we used Excel to analyse bike sales data, to determine the customers most likely to buy a bike. 

## Quick Links
- Bike buyers dataset: [Bike Buyers Dataset](bike_buyers_dataset.xlsx)
- Final dashboard of bike sales: [Bike Sales Dashboard](bike_sales_dashboard.png)
- Bike sales excel project file: [Excel Project File](bike_sales_project.xlsx)
- Other projects I have made: [Portfolio Website](https://lucashoffschmidt.github.io/)

## Technologies Used
- **Excel**: Data cleaning, data exploration and creation of final dashboard.

## Process
- **Data Cleaning**:
  - Opened the excel dataset of bike buyers.   
  - Created separate sheets for cleaning, pivot tables and the dashboard.
  - Removed duplicates using data -> remove duplicates.
  - Replaced single letter values with full words using find and replace.
  - Changed format of Income column to currency and removed decimals.
  - Created age brackets using IF conditions.
- **Data Exploration and Dashboard Creation**:
  - Made a pivot table for gender, average income and if the person purchased a bike. 
    - Created a clustered column chart from it.
    - Formatted the table to numbers and removed decimals.
  - Made a pivot table for commute distance and bikes purchased. 
    - Made a line chart from it.
    - Renamed "10+ Miles" to "More than 10 Miles".
  - Made a pivot table for age bracket, bike purchases and if the person purchased a bike.
    - Made a line chart from it.
  -  Combined all charts into a dashboard with a header and even spacing. 
  -  Added slicers for marital status, region and education.
  -  Linked slicers to all charts using PivotTable Connections.

## Key findings
- Higher income indicates higher likelihood of buying a bike.
- The majority of customers are between 31-55 years old.
- Most customers have a commute of less than a mile.

## Final dashboard
![Bike Sales Dashboard](bike_sales_dashboard.png)

## Conclusion
The analysis indicates that the people most likely to buy a bike has one or more distinguishing characteristics: higher income, being between 31-55 years old and having a commute of less than a mile. 
