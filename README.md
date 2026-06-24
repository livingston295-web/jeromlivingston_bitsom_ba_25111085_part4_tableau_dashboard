# Tableau Executive Dashboard & Data Storytelling

## Business Problem Summary

The objective of this project is to create an executive dashboard for retail business leadership. The dashboard helps monitor sales performance, profitability, customer segments, category performance, shipping performance, discount impact, and return patterns.

## Dataset Description

The dataset contains retail sales transaction data including:

* Order Date
* Ship Date
* Region
* Customer Segment
* Category
* Sub Category
* Sales
* Profit
* Discount
* Return Flag
* Delivery Days
* Campaign Channel

## Tableau Workbook Description

The Tableau workbook contains an interactive Executive Dashboard that enables business users to analyze performance across multiple dimensions.

Workbook File:

* executive_dashboard.twbx

## Calculated Fields Created

1. Profit Margin = Profit / Sales
2. Cost = Sales - Profit
3. Average Order Value = Sales / Number of Orders
4. Return Rate = Returned Orders / Total Orders
5. Shipping Delay Bucket = Fast, Normal, Delayed

## Dashboard Components

The dashboard includes:

* Sales Trend View
* Regional Performance View
* Category Profitability View
* Customer Segment View
* Shipping Performance View
* Discount vs Profit View
* Return Analysis View

## KPI Cards

The dashboard displays:

* Total Sales
* Total Profit
* Profit Margin
* Return Rate

## Filters and Interactions Used

Interactive filters used:

* Region
* Category
* Customer Segment
* Return Flag

Dashboard interactions allow users to explore specific regions and business segments.

## Key Business Insights

* Sales remain relatively stable across the reporting period.
* Certain regions generate higher sales and profit.
* Technology products contribute strong profitability.
* Customer segments show different purchasing behaviors.
* High discounts do not always improve profit.
* Shipping delays may impact customer satisfaction.
* Return patterns highlight areas requiring investigation.
* Growth opportunities exist in profitable regions and categories.

## Dashboard Story Summary

The dashboard helps leadership identify business strengths, weaknesses, risks, and opportunities. It supports decision-making related to sales growth, profitability improvement, operational efficiency, and customer satisfaction.

## Assumptions

* Dataset values are accurate.
* Return Flag correctly identifies returned orders.
* Delivery Days accurately represent shipping performance.

## Limitations

* Historical data only.
* External market factors are not included.
* Additional analysis may be required for root-cause investigation.

## Screenshots Included

* full_dashboard.png
* sales_trend_view.png
* regional_performance_view.png
* category_profitability_view.png
* filter_interaction_view.png
