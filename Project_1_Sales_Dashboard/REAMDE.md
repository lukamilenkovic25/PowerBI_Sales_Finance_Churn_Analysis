# Project 1: Sales Dashboard (2023–2025)

## Overview
This project provides an interactive Power BI dashboard for analyzing sales performance from 2023 to 2025.  
The report focuses on revenue trends, product performance, and regional insights.

## Business Questions
- How are revenue and quantity trending over time?
- Which products and regions generate the highest sales?
- What is the YTD, YoY, and MoM performance?
- How do product categories compare?

## Key Insights
- Clear upward and downward trends across months and years
- Highest-performing products identified through ranking logic
- Regional comparison highlights strong and weak markets
- Category-level contribution analysis

## Data & Modeling
- ETL performed in Power Query (cleaning, type fixing, transformation)
- A star schema was used:
  - Fact table: Sales transactions
  - Dimension tables: Date, Product, Region
- Time intelligence enabled through a dedicated Date Table

### Data Model
Project_1_Sales_Dashboard/Image/Sales_Data_Model.png

## DAX Highlights
- YTD, YoY and MoM performance indicators
- Category and product ranking measures
- KPI calculations for revenue and quantity

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Data Modeling (Star Schema)
- Analytical storytelling

## Files Included
- PBIX report
- Images for all dashboard pages
- Data model screenshot
- DAX folder with measure examples
