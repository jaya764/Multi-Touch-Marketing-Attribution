# Multi-Touch-Marketing-Attribution & ROI Dashboard

## Project Overview
Analysis of 586k row marketing attribution dataset to understand which marketing channels drive the most conversions and revenue.

## Tools Used
-Python (Pandas,Matplotlib)
-SQLite (Advanced SQL)
Jupyter Notebook
GitHub

## Week 1 - EDA
-Data cleaning, duplicate removal, EDA
-Channel analysis and visualizations

## Week 2 - SQL Analysis
-Loaded cleaned into SQLite database
-Window Functions, First Click, Linear, Last Click Attribution
-Channel conversion rate, revenue analysis
-Key insights summary

## Key Findings
-Paid Search dominates first touch (76,210)
-Facebook generates highest revenue (₹33,143.5)
-Average user converts after 1 touchpoint

## Week 3 - Metric Calculation & Data Modeling

**KPI Results**
|Channel|Spend|CPC|CAC|ROAS|
|-------|-----|---|---|----|
|Facebook|12000|1.67|2.26|2.76|
|Instagram|8000|1.57|3.57|1.75|
|Online video|6000|1.58|1.76|3.57|
|Online display|4000|1.38|1.87|3.32|
|Paid Search|15000|1.76|3.30|1.89|

## Star Schema
* dim_channel - 5 channels
* dim_date - unique dates
* dim_user - 240,108 unique users
* dim_interaction - 2 interactions
* fact_conversions - 17,639 records

## Key Findings
* Online Video has highest ROAS(3.57)
* Facebook has highest conversions(5301)
* Paid search has highest spend(₹15000)

## Visualizations
* ROAS by Channel
* Total Conversions by Channel
* Ad Spend by Channel

## Week 4 - Power BI Dashboard

## Dashboard Visuals
- Revenue by Marketing Channel (Bar Chart)
- Number of Conversions (Bar Chart)
- Daily Revenue Trend - July 2018 (Line Chart)
- ROI Analysis - Spend vs Revenue (Scatter Plot)
- Attribution Model Comparison (Clustered Bar Chart)
- Conversion Funnel (Funnel Chart)
- 4 KPI Cards : Total Revenue, Total Spend, Total Conversions, Conversion Rate

## Key Findings
- Facebbok: Highest revenue(₹33,143) and conversions(5,301)
- Online Video: Best ROAS(3.57)
- Paid Search: Dominates all 3 attribution models
- Overall Conversion Rate: 7,58%
- Total Revenue: ₹1,10,231
- Total Ad Spend: ₹45,000

  <img width="1365" height="762" alt="Marketing Dashboard" src="https://github.com/user-attachments/assets/454acff7-a34c-4a54-ad31-2f6b38a64b6b" />


