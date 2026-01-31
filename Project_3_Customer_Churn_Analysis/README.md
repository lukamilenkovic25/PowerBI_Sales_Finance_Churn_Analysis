# Project 3: Customer Churn Analysis

## Overview
This project analyzes customer churn with the goal of identifying drivers of churn and patterns in customer behavior.

## Business Questions
- What is the churn rate and how does it differ by demographic segment?
- Which customer groups have the highest churn risk?
- How does engagement and spending relate to churn?
- What factors most strongly influence churn?

## Key Insights
- Churn is strongly correlated with lower engagement levels
- Certain age groups show significantly higher churn
- Country-level churn differences highlight geographic patterns
- Spending analysis reveals clear behavioral differences

## Data & Modeling
- Power Query used for data cleaning and transformation
- Star schema:
  - Fact table: Customers
  - Dimension tables: Date, Demographics, Country
- Segmentation logic implemented in DAX

### Data Model
./Customer_Churn_Data_Model.png

## DAX Highlights
- Churn rate calculation
- Active vs churned segmentation
- Customer behavior KPIs

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Analytical storytelling

## Files Included
- PBIX report
- Dashboard images
- Data model screenshot
- DAX folder
