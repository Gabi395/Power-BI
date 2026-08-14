# Online Retail Sales Analysis

## Overview
Power BI dashboard analyzing online retail sales data from a UK-based retailer (2011).

## Data
- **Source:** Online Retail dataset
- **Records:** ~4,000 transactions
- **Period:** 2011

## Features
- Total Revenue KPI card
- Revenue by Month (line chart)
- Top 10 Products by Revenue (bar chart)
- Revenue by Country (bar chart)
- Interactive slicers (Year, Country)

## Data Model
Star schema with:
- **FactSales** – transactions
- **DimProduct** – product details
- **DimCustomer** – customer and country info
- **DimDate** – date table

## DAX Measures
- Total Revenue (SUMX)
- Number of Customers (DISTINCTCOUNT)
- Number of Invoices (DISTINCTCOUNT)
- Revenue by Country (CALCULATE)
- Revenue YTD (TOTALYTD)

## Tools
- Power BI Desktop
- Power Query
- DAX
