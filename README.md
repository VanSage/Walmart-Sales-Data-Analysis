# 📊 Walmart Sales Trend & Performance Analysis

## Overview

This project presents an Exploratory Data Analysis (EDA) of Walmart sales data using Python. The objective is to uncover sales trends, seasonal patterns, holiday impacts, and the influence of economic indicators on weekly sales performance.

By leveraging data visualization and statistical analysis techniques, this project transforms raw sales data into actionable business insights that can support strategic decision-making.

---

## Business Problem

Retail organizations generate large volumes of sales data every week. Understanding how sales are affected by seasonality, holidays, economic conditions, and store performance is critical for inventory planning, revenue forecasting, and operational efficiency.

This project aims to answer the following questions:

* How do Walmart sales change over time?
* Do holidays significantly impact weekly sales?
* Which stores perform the best?
* Are economic factors such as CPI, Fuel Price, and Unemployment related to sales performance?
* What insights can be extracted through data visualization and correlation analysis?

---

## Dataset Information

The dataset contains **6,435 records** and **8 features**.

| Feature      | Description                                      |
| ------------ | ------------------------------------------------ |
| Store        | Store Identification Number                      |
| Date         | Weekly Observation Date                          |
| Weekly_Sales | Weekly Sales Revenue                             |
| Holiday_Flag | Holiday Indicator (1 = Holiday, 0 = Non-Holiday) |
| Temperature  | Weekly Average Temperature                       |
| Fuel_Price   | Fuel Price During the Week                       |
| CPI          | Consumer Price Index                             |
| Unemployment | Unemployment Rate                                |

---

## Tools & Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Project Workflow

### 1. Data Collection

* Imported Walmart sales dataset.
* Loaded data into Pandas DataFrame.

### 2. Data Preparation

* Checked data types and structure.
* Verified missing values.
* Converted Date column to datetime format.
* Extracted Month and Year features.

### 3. Exploratory Data Analysis

* Weekly Sales Trend Analysis
* Store Performance Analysis
* Holiday Impact Analysis
* Monthly Sales Pattern Analysis
* Economic Indicator Analysis

### 4. Data Visualization

* Line Charts
* Bar Charts
* Scatter Plots
* Correlation Heatmap

### 5. Insight Generation

* Identified sales trends.
* Evaluated holiday effects.
* Examined store-level performance.
* Analyzed relationships between sales and economic factors.

---

## Key Findings

### 📈 Sales Trends

* Weekly sales fluctuate significantly across the observed period.
* Several peaks indicate periods of increased consumer demand.

### 🏬 Store Performance

* Certain stores consistently outperform others.
* Sales distribution varies significantly between locations.

### 🎉 Holiday Impact

* Holiday weeks generally experience higher average sales compared to non-holiday weeks.
* Seasonal shopping behavior contributes to revenue spikes.

### 📅 Seasonal Patterns

* Monthly sales analysis reveals recurring seasonal trends.
* Customer purchasing behavior varies throughout the year.

### 📊 Economic Factors

* CPI, Fuel Price, and Unemployment exhibit varying levels of influence on sales.
* Store-specific and seasonal factors appear to have a stronger impact than macroeconomic variables.

---

## Visualizations Included

* Weekly Sales Trend
* Store Performance Comparison
* Holiday vs Non-Holiday Sales Analysis
* Monthly Sales Pattern Analysis
* Temperature vs Sales Analysis
* Fuel Price vs Sales Analysis
* CPI vs Sales Analysis
* Unemployment vs Sales Analysis
* Correlation Heatmap

---

## Project Structure

```text
Walmart-Sales-Data-Analysis/
│
├── Walmart.csv
├── Walmart_Sales_Analysis.ipynb
├── Project_Report.pdf
└── README.md
```

---

## Results

The analysis demonstrates how data analytics can be used to identify business trends, understand customer behavior, and evaluate the impact of external economic factors on retail sales performance.

The findings can support:

* Demand Forecasting
* Inventory Management
* Holiday Sales Planning
* Business Performance Monitoring
* Data-Driven Decision Making

---

## Future Enhancements

* Sales Forecasting using Machine Learning
* Interactive Dashboard Development using Power BI
* Advanced Time-Series Analysis
* Store Segmentation and Clustering
* Predictive Analytics for Holiday Sales

---

## Author

**Vanshika**

Data Analytics Internship Project

Python | Data Analytics | Exploratory Data Analysis | Business Intelligence

---

⭐ If you found this project useful, consider giving it a star!
