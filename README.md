# FlipViz — Flipkart Sales Performance Dashboard

An end-to-end sales analytics project that cleans and analyzes Flipkart transaction data in Python, then visualizes revenue trends, product performance, and payment behavior through an interactive Power BI dashboard.

## Overview

This project takes raw Flipkart sales data through a full analysis pipeline: cleaning and exploration in Python, followed by an interactive Power BI dashboard for business-facing insights. It answers practical retail questions — which categories drive the most revenue, when sales peak, and how customers prefer to pay.

## Dashboard Preview

![FlipViz Dashboard](Flipkart%20Dashboard.png)

## Tools Used

Python, Pandas, Matplotlib, Power BI

## Features

- Revenue trend analysis over time
- Category and product-level performance breakdown
- Payment method distribution and insights
- KPI summary cards: total revenue, order count, average order value

## Key Insights

- The Electronics category drives the highest share of total revenue
- Sales volume peaks during the mid-year months
- Digital payment methods are used far more than cash on delivery

## Repository Structure

```
Sales Analysis.ipynb              Python notebook: data cleaning, exploration,
                                   and preliminary analysis with Pandas/Matplotlib

flipkart sales data analysis.pbix Power BI file containing the interactive
                                   dashboard

flipkart_sales.csv                 Raw sales data

final_sales_data.csv               Cleaned dataset, output of the notebook and
                                   input to the Power BI dashboard

Flipkart Dashboard.png             Dashboard preview screenshot

Requirements.txt                   Python dependencies
```

## How to Run

**Python analysis:**
```
pip install -r Requirements.txt
jupyter notebook "Sales Analysis.ipynb"
```

**Power BI dashboard:**
Open `flipkart sales data analysis.pbix` in Power BI Desktop. Power BI Desktop is free and available for Windows from Microsoft.

## Methodology

Raw sales data is loaded and cleaned in the Python notebook — handling missing values, correcting data types, and deriving fields needed for analysis (such as order value and time-based groupings). The cleaned dataset (`final_sales_data.csv`) is then connected to Power BI, where it's shaped into KPI cards, trend charts, and category breakdowns for the final interactive dashboard.
