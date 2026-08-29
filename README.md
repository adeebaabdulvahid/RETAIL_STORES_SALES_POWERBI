## Retail Store Sales Analysis Dashboard

## Project Overview

This project presents an interactive Retail Store Sales Analysis Dashboard developed using Microsoft Power BI.

The dashboard is designed to analyze sales performance, transaction trends, customer activity, product performance, payment methods, and sales channels.

## Dashboard Features

- KPI cards for key business metrics
- Monthly sales trend analysis
- Sales analysis by category
- Sales analysis by location
- Sales analysis by payment method
- Top 10 items by sales
- Interactive Year, Month, Category, Location, and Payment Method slicers
- Drill-down analysis: Year → Quarter → Month → Date
- Drill-through analysis by category
- Power BI bookmarks for dashboard views
- Interactive filtering and navigation

## Report Pages
Page 1 — Retail Store Sales Performance Dashboard
Provides an overall summary of retail sales performance using KPI cards, slicers, and multiple visualizations.

### Page 2 — Sales Drill-Down Analysis
Provides hierarchical sales analysis using:
Year → Quarter → Month → Date

### Page 3 — Detailed Sales Drill-Through Analysis
Provides detailed analysis for a selected category, including sales, transactions, top items, sales trends, payment methods, and location.

## Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- GitHub

## Project Deliverables

- Power BI Dashboard (`.pbix`)
- Interactive dashboard pages
- Drill-down and drill-through functionality
- Power BI bookmarks

## Data Preparation

The Excel dataset was prepared before importing it into Power BI.

The data preparation process included:

- Reviewing the dataset structure and columns
- Checking for missing/null values
- Verifying and correcting data types
- Ensuring Transaction Date was stored as a proper date
- Checking the consistency of the dataset
- Using the cleaned dataset as the source for the Power BI report

## Data Modeling

The prepared Excel data was imported into Power BI and modeled using:

- A `Cleaned_Data` table for the sales transactions
- A `Dim_Date` table for date-based analysis
- A relationship between the transaction data and date table
- DAX measures for sales, transactions, quantity, customers, and other KPIs

