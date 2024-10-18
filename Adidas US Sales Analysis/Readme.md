# Adidas US Sales Analysis

## Overview
This project provides a comprehensive analysis of Adidas' sales data in the US, sourced from [Kaggle](https://www.kaggle.com/). The goal is to derive actionable insights into sales trends, product performance, and regional demand through a full data operations pipeline. The analysis involves Data Cleaning, Transformation, Exploratory Data Analysis (EDA), and Dashboard Visualizations.

## Project Objectives
- **Understand** overall sales trends and performance by region, season, and product category.
- **Identify** top-selling products and periods of peak sales.
- **Analyze** regional differences in sales and product demand.
- **Visualize** insights through a user-friendly dashboard for further business decision-making.

## Data Operations

### 1. Data Cleaning
- **Missing Values**: Handled using appropriate strategies (e.g., median imputation, mode for categorical data).
- **Duplicates**: Identified and removed duplicate entries to maintain data integrity.
- **Data Types**: Corrected inconsistent data types (e.g., converting sales figures to numeric, dates to `datetime` format).

### 2. Data Transformation
- **Feature Engineering**: Created new columns such as `Month`, `Quarter`, `Year`, and `Sales_Percentage` to assist in trend analysis.
- **Normalization**: Applied to sales data for consistency across different regions.
- **Aggregation**: Grouped data by product category, region, and time period to facilitate macro-level analysis.

### 3. Exploratory Data Analysis (EDA)
- **Sales Trends**: Analyzed total sales over time to spot growth patterns and seasonal impacts.
- **Regional Performance**: Compared sales between different states and regions to identify high/low-performing areas.
- **Product Analysis**: Evaluated the top-selling products and categories using bar charts and histograms.
- **Correlation**: Investigated relationships between variables like price, sales, and product categories using heatmaps.

### 4. Dashboard Showcase
The insights from the analysis were visualized using an interactive dashboard. The dashboard provides:
- **Sales Overview**: A high-level view of total sales across different periods.
- **Product Performance**: A breakdown of sales by product categories and top sellers.
- **Geographical Insights**: Visualizations highlighting regional differences in sales performance.
- **Seasonal Trends**: Line charts showing how sales vary by month and quarter.

![Dashboard Screenshot](https://github.com/DhruvilPanchal205/Power-BI-Dashboards/blob/main/Adidas%20US%20Sales%20Analysis/Screenshot%202024-10-18%20000622.png)
[Download PDF of Dashboard Report](https://github.com/DhruvilPanchal205/Power-BI-Dashboards/blob/main/Adidas%20US%20Sales%20Analysis/Dashboard.pdf)

## Technologies Used
- **Python**: Data manipulation and analysis using libraries like Pandas and NumPy.
- **Power BI / Tableau**: For building the interactive dashboard.
- **Jupyter Notebook**: Development environment for running the analysis and visualizations.
- **Kaggle**: Data source for Adidas sales dataset.

## Conclusion
Through this project, we uncovered key insights into Adidas' sales performance in the US, identified seasonal and regional trends, and created a dashboard to help stakeholders make data-driven decisions. This analysis can guide future marketing and sales strategies to optimize revenue.


