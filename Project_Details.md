# Project Details — Sales & Profit Analysis Dashboard

## 1. Project Title

**Sales & Profit Analysis Dashboard**

## 2. Project Type

**Business Intelligence / Data Analytics / Power BI Dashboard**

## 3. Objective

The objective of this project is to convert transactional sales data into an interactive Power BI dashboard that helps users monitor revenue, cost, profit, product performance, regional performance, salesperson performance, order status, and trends over time.

The project is intended to demonstrate how a Data Analyst can move from raw Excel data to an interactive business intelligence report.

## 4. Business Problem

A sales organization may have a large number of transactions but still lack a simple way to answer important management questions.

This project addresses questions such as:

- What is the total sales and profit?
- Which products generate the highest sales?
- Which categories are most valuable?
- Which regions perform best?
- How is sales performance changing month by month?
- Which salespersons generate the most revenue?
- How do discounts affect profitability?
- How many orders are delivered, shipped, or cancelled?
- Which areas require management attention?

## 5. Data Source

The primary source is the uploaded Excel workbook:

`Sales_Profit_Analysis_Dashboard_Portfolio.xlsx`

The workbook contains 1,000 sales transactions plus supporting product, salesperson, and calendar tables.

### Reporting Period

**01 April 2025 – 31 March 2026**

## 6. Data Tables

### Sales Table

The main transaction table contains:

- Order ID
- Order Date
- Customer
- Region
- State
- Category
- Product ID
- Product
- Quantity
- Unit Price
- Discount %
- Discount Amount
- Sales
- Cost
- Profit
- Salesperson
- Payment Mode
- Order Status

### Products Table

Contains product master information:

- Product ID
- Product
- Category
- List Price

### Salespersons Table

Contains:

- Salesperson
- Team
- Target

### Calendar Table

Contains:

- Date
- Year
- Month Number
- Month
- Month Year
- Month Year Sort
- Financial Year

## 7. Data Preparation

The project uses a structured Excel workbook so that the Power BI report can separate transaction data from supporting dimension tables.

Typical preparation/modeling activities include:

- Checking column data types
- Using a dedicated calendar table
- Creating appropriate relationships between tables
- Sorting Month Year using Month Year Sort
- Preparing fields for filtering and aggregation
- Validating sales, cost, profit, quantity, discount, and order-status fields

## 8. Key Measures / KPIs

The project is designed around core business KPIs such as:

### Total Sales

Sum of the `Sales` field.

### Total Cost

Sum of the `Cost` field.

### Total Profit

Sum of the `Profit` field.

### Profit Margin

```text
Profit Margin = Total Profit / Total Sales
```

### Total Quantity

Sum of the `Quantity` field.

Additional measures can be used for:

- Sales by month
- Profit by month
- Sales by region
- Profit by region
- Sales by category
- Sales by product
- Salesperson performance
- Target achievement
- Order-status analysis

## 9. Source Data Reference Results

Calculated from the uploaded Excel source:

| KPI | Result |
|---|---:|
| Total Sales | ₹13,087,366.26 |
| Total Cost | ₹10,013,534.23 |
| Total Profit | ₹3,073,832.03 |
| Profit Margin | 23.49% |
| Total Quantity | 3,927 |
| Discount Amount | ₹1,043,062.84 |

### Top-Level Reference Findings

| Analysis | Result |
|---|---|
| Highest-sales category | Furniture |
| Highest-sales product | Filing Cabinet |
| Highest-sales region | North |
| Number of customers | 294 |
| Number of products | 20 |
| Number of regions | 4 |

## 10. Dashboard Design

The Power BI report should present the analysis in a clean business-reporting format.

Recommended dashboard sections include:

### Executive Summary

High-level KPI cards and major sales/profit trends.

### Sales Trend

Monthly sales and profit trends using the Calendar table.

### Product & Category Performance

Comparison of sales and profit across products and categories.

### Regional Performance

Region and state-level sales/profit comparison.

### Salesperson Performance

Sales and profit by salesperson, with target comparison where applicable.

### Order & Discount Analysis

Order status and discount impact on sales/profitability.

## 11. Business Value

The dashboard demonstrates how raw transaction records can be transformed into information that supports:

- Sales monitoring
- Profitability monitoring
- Product decisions
- Regional performance review
- Salesperson evaluation
- Trend analysis
- Discount evaluation
- Management reporting

## 12. Skills Demonstrated

### Technical Skills

- Microsoft Excel
- Power Query
- Power BI
- DAX
- Data modeling
- Data visualization
- KPI creation
- Date-table design

### Analytical Skills

- Sales analysis
- Profitability analysis
- Trend analysis
- Product analysis
- Category analysis
- Regional analysis
- Salesperson performance analysis
- Business KPI interpretation

## 13. Portfolio / Interview Explanation

A concise way to explain this project in an interview:

> “I built a Sales & Profit Analysis Dashboard in Power BI using a 1,000-record Excel sales dataset. I structured the data into transaction and supporting tables, used a calendar table for time analysis, created business KPIs for sales, cost, profit and margin, and designed interactive analysis for products, categories, regions and salespersons. The objective was to turn raw sales transactions into a management-friendly dashboard for monitoring performance and profitability.”

## 14. Files Included

```text
Dataset/
└── Sales_Profit_Analysis_Dashboard_Portfolio.xlsx

PowerBI/
└── SALES & PROFIT ANALYSIS DASHBOARD.pbix

Screenshots/
└── Dashboard screenshots can be added here

Documentation/
└── Project_Details.md
```

## 15. Limitations / Notes

- The `.pbix` file is the actual Power BI report and should be opened in Power BI Desktop.
- The Excel workbook is the source dataset supplied with this portfolio project.
- Dataset-level KPI calculations in this document are reference calculations from the Excel source.
- Dashboard screenshots should be added after final visual formatting so the GitHub repository reflects the actual final report.

## 16. Future Improvements

Possible future enhancements include:

- Adding more advanced DAX measures
- Adding target-achievement KPIs
- Adding drill-through pages
- Adding tooltip pages
- Adding year-over-year comparisons
- Adding dynamic titles
- Adding a dedicated executive summary page
- Adding automated data refresh through a cloud data source
- Adding SQL as an alternative data source

## 17. Project Outcome

The completed project demonstrates an end-to-end BI workflow:

**Excel Dataset → Data Preparation → Data Model → DAX Measures → Power BI Visualizations → Business Insights**

This makes the project suitable as a portfolio example for **Data Analyst, MIS Analyst, Reporting Analyst, and Power BI Analyst** applications.
