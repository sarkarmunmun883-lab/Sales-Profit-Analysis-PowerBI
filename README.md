# Sales & Profit Analysis Dashboard | Power BI

A portfolio-ready **Power BI sales analytics project** built to analyze sales performance, profitability, products, categories, regions, customers, and salespersons using a structured 1,000-record sales dataset.

## Project Overview

This dashboard transforms transactional sales data into an interactive management report. It is designed to answer common business questions such as:

- How much are we selling?
- How much profit are we generating?
- Which products and categories perform best?
- Which regions contribute the most sales and profit?
- How does performance change over time?
- Which salespersons contribute the most revenue?
- Where are discounts, cancellations, or weak performance affecting results?

## Key Dataset Facts

| Metric | Value |
|---|---:|
| Sales records | 1,000 |
| Customers | 294 |
| Products | 20 |
| Categories | 4 |
| Regions | 4 |
| States | 16 |
| Salespersons | 8 |
| Total quantity | 3,927 |
| Date range | 01 Apr 2025 – 31 Mar 2026 |

## Dataset-Level Summary

These figures are calculated from the uploaded Excel source file and are included as a reference for the project documentation.

| KPI | Value |
|---|---:|
| Total Sales | ₹13,087,366.26 |
| Total Cost | ₹10,013,534.23 |
| Total Profit | ₹3,073,832.03 |
| Profit Margin | 23.49% |
| Discount Amount | ₹1,043,062.84 |

> **Note:** The exact visual values shown in the Power BI report should be taken from the `.pbix` dashboard. The figures above are dataset-level reference calculations from the uploaded Excel workbook.

## Business Insights from the Source Data

- **Top sales category:** Furniture
- **Top sales product:** Filing Cabinet
- **Top sales region:** North
- The dataset contains delivered, shipped, and cancelled orders, enabling order-status analysis.
- The dataset includes discount information, making discount-versus-profit analysis possible.
- Salesperson targets are available in the supporting `Salespersons` table for performance-versus-target analysis.

## Tools & Technologies

- **Power BI Desktop**
- **Power Query** for data preparation
- **DAX** for calculated measures and KPIs
- **Microsoft Excel** as the source dataset
- Data modeling / relationships
- Interactive filters and slicers
- KPI cards and business charts

## Dataset Structure

The Excel workbook contains these sheets:

### `Sales`
Transactional sales data including:

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

### `Products`
Product master data containing product, category, and list price information.

### `Salespersons`
Salesperson information including team and target.

### `Calendar`
A dedicated date table covering the reporting period, including month, month-year, sort order, and financial year fields.

### `Excel_KPI_Guide`
Reference area for KPI calculations.

## Suggested Dashboard Analysis

The project is designed around the following analytical areas:

1. **Executive Overview**
   - Total Sales
   - Total Profit
   - Total Cost
   - Profit Margin
   - Order / quantity overview

2. **Time Analysis**
   - Monthly sales trend
   - Monthly profit trend
   - Financial-year analysis

3. **Product & Category Analysis**
   - Top products
   - Category performance
   - Sales and profit contribution

4. **Regional Analysis**
   - Region-wise sales
   - Region-wise profit
   - State-level performance

5. **Salesperson Analysis**
   - Salesperson sales
   - Profit contribution
   - Target comparison

6. **Order & Discount Analysis**
   - Delivered / shipped / cancelled orders
   - Discount impact
   - Profitability analysis

## Repository Structure

```text
Sales-Profit-Analysis-PowerBI/
│
├── README.md
│
├── Dataset/
│   └── Sales_Profit_Analysis_Dashboard_Portfolio.xlsx
│
├── PowerBI/
│   └── SALES & PROFIT ANALYSIS DASHBOARD.pbix
│
├── Screenshots/
│   └── Add dashboard screenshots here
│
└── Documentation/
    └── Project_Details.md
```

## How to Use

1. Download or clone this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. If Power BI asks for the source file, point it to the Excel workbook inside the `Dataset` folder.
4. Refresh the data if required.
5. Use the dashboard slicers and visual interactions to explore the analysis.

## Portfolio Skills Demonstrated

This project demonstrates practical skills relevant to **Data Analyst / MIS / Power BI Analyst** roles:

- Data cleaning and transformation
- Data modeling
- Power Query
- DAX
- KPI development
- Business dashboard design
- Sales and profitability analysis
- Time-series analysis
- Regional analysis
- Product analysis
- Salesperson performance analysis
- Interactive reporting
- Business storytelling with data

## Author

**Munmun**

Data Analyst Portfolio Project  
Skills: Excel | Power Query | Power BI | DAX | Data Analysis

---
*This repository contains a portfolio project created for learning, demonstration, and job-application purposes.*
