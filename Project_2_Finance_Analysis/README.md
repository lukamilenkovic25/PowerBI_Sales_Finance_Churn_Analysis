# Project 2: Finance & Cost Control Dashboard

## Overview
This Power BI dashboard provides a financial overview with a focus on budget vs actual spending, variance tracking, and cost optimization.

## Business Questions
- Which departments exceed their budget?
- What are the cost trends over time?
- Which cost types drive the largest deviations?
- How well is the organization utilizing its approved budget?

## Key Insights
- Clear visibility into budget utilization and variance %
- Identification of overspending departments
- Monthly and yearly cost trend analysis
- Detailed breakdown of cost categories

## Data & Modeling
- Budget and Actual tables cleaned and merged in Power Query
- Star schema model:
  - Fact table: Financials (Budget + Actual merged)
  - Dimension: Date, Department, Country, Category
- Custom variance measures (absolute and percentage)

### Data Model
Project_2_Finance_Analysis/Image/Finance_Data_Model.png

## DAX Highlights
- Variance calculations (Budget – Actual)
- Variance %
- Department ranking by total cost

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Financial KPI analysis

## Files Included
- PBIX report
- Dashboard page images
- Data model screenshot
- DAX folder
