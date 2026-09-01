# superstore-excel-dashboard
Superstore sales dashboard built in WPS Office using PivotTables, KPIs, charts, data-quality analysis, and business insights.
# Superstore Sales Dashboard

## Project Overview

This project analyzes the Superstore dataset to understand sales and profit performance across different regions, categories, customer segments, and time periods.

I built a one-page dashboard in WPS Office to summarize key business metrics and communicate analytical findings through PivotTables, KPIs, and charts.

## Tool Used

- WPS Office Spreadsheet

## Skills Practiced

- PivotTables
- PivotCharts
- SUMIFS
- COUNTIFS
- AVERAGEIFS
- XLOOKUP
- INDEX/MATCH
- IF
- IFERROR
- TRIM
- Data cleaning
- Data-quality analysis
- Dashboard design
- Business insight generation

## Data Quality Analysis

I checked the dataset for:

- Missing values
- Duplicates
- Data types
- Text consistency

During the analysis, I identified one incomplete transaction with missing values in:

- Sales
- Quantity
- Discount
- Profit

I did not automatically replace the missing values with zero. The recommended approach was to verify the original source data before making any changes.

## Data Transformation Concepts Practiced

### Merge

Combined related tables using a common key such as Customer ID.

### Append

Combined multiple tables by stacking their rows.

### Unpivot

Converted data from a wide format into a long format to make monthly analysis easier.

## Dashboard KPIs

The dashboard includes:

- Total Sales
- Total Profit
- Profit Margin
- Total Orders
- Total Customers

## Dashboard Visualizations

The dashboard includes:

- Regional Sales & Profit
- Monthly Sales Trend
- Profit by Category
- Regional Sales
- Sales by Segment

### Chart Types Used

- Bar charts for regional and category comparisons
- Line chart for monthly sales trends
- Donut chart for sales by segment

## Key Business Insights

- The West region generated the highest sales: **$73,725.27**.
- Office Supplies generated the highest profit in my analysis: **$12,962.04**.
- The Home Office segment had the highest average sales in my analysis: **$296.19**.
- Furniture showed a loss of approximately **$794.57** in the analysis.

These findings are based on the analysis performed on the Superstore dataset.

## Dashboard Preview

![Superstore Dashboard](screenshots/dashboard.png)

## Supporting Analysis

### KPI PivotTable

![KPI PivotTable](screenshots/kpi-pivottable.png)

### Monthly Sales Trend

![Monthly Sales Trend](screenshots/monthly-sales-trend.png)

## Project File

The complete workbook is available here:

[Download the Excel Dashboard](Superstore_Sales_Dashboard.csv)

## Learning Outcome

This project helped me practice spreadsheet-based data analysis, data-quality checking, PivotTables, PivotCharts, data transformation concepts, dashboard design, and translating analytical results into business insights.

## Future Improvements

- Rebuild the dashboard in Power BI
- Add more advanced analytical measures
- Improve interactive filtering
- Perform deeper profitability analysis
