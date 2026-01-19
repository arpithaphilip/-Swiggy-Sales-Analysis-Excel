# Swiggy Sales Analysis – Excel

This project focuses on analyzing Swiggy sales data using Microsoft Excel to derive meaningful business insights.

## Key Features
- Built an Excel-based sales dashboard using Pivot Tables and formulas to track key KPIs.
- Analyzed monthly, weekly, and daily sales trends to identify peak periods.
- Performed category-wise and location-wise analysis using slicers and filters for interactive insights.

## Tools Used
- Microsoft Excel
- Pivot Tables & Pivot Charts
- Excel Functions (MONTH, WEEKNUM, INT)

## Outcome
The dashboard enables quick analysis of sales performance, customer behavior, and regional trends to support data-driven decision-making.

# -Swiggy-Sales-Analysis-Excel
An Excel-based sales analysis dashboard built using pivot tables, charts, and formulas to track sales performance, order trends, and customer ratings. The project provides insights into time-based trends, food categories, and top-performing locations with interactive filters for easy analysis.
## Formulas Used

- MONTH() – Extracted month from order date for monthly analysis.
- WEEKNUM() – Calculated week number to perform weekly sales trend analysis.
- INT() – Used for rounding down values in quarter calculations.
- Quarter Calculation:
  ="Q"&INT((MONTH([@[Order Date]])-1)/3)+1
- SUMIFS() – Calculated total sales based on multiple conditions.
- COUNTIFS() – Counted total orders using conditional logic.
- AVERAGE() – Calculated average order value (AOV) and ratings.
