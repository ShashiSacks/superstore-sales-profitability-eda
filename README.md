# Superstore Sales & Profitability Analysis

## Overview

An end-to-end exploratory data analysis project using Python to analyze sales, profitability, customer segments, products, regions, discounts, and time-based trends in the Superstore dataset.

The project focuses on transforming raw business data into meaningful insights through data cleaning, feature engineering, exploratory data analysis, statistical analysis, and visualization.

## Objectives

- Understand and clean the raw Superstore dataset
- Analyze sales and profitability patterns
- Identify trends across products, categories, customers, and regions
- Examine the relationship between discounts and profitability
- Analyze sales and profit trends over time
- Identify potential outliers and unusual patterns
- Generate business-oriented insights from the data

## Dataset

**Dataset:** Superstore Sales Dataset

The dataset contains information related to:

- Orders and shipping
- Customers and customer segments
- Products and categories
- Geographical regions
- Sales and quantities
- Discounts
- Profits

The dataset contains **9,994 rows and 21 columns**.

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Understanding
3. Data Quality Assessment
4. Data Cleaning
5. Data Transformation & Feature Engineering
6. Exploratory Data Analysis
7. Statistical Analysis
8. Data Visualization
9. Business Insights
10. Recommendations

## Analysis Questions

The analysis investigates questions such as:

- Which categories and sub-categories generate the most sales?
- Which categories and sub-categories generate the most profit?
- Which products contribute to losses?
- How does discounting relate to profitability?
- Which regions and customer segments perform better?
- How do sales and profit change over time?
- Are there relationships between sales, discount, quantity, and profit?
- Which products contribute most to overall profitability?
- Are there unusual or extreme values in the numerical variables?

## Key Findings

- Analyzed overall sales, profit, and profit margins across the dataset.
- Compared sales and profitability across categories and sub-categories.
- Identified products that contribute to overall losses and products with strong profitability.
- Analyzed regional and customer-segment performance.
- Examined the relationship between discounts and profitability.
- Analyzed yearly and monthly sales and profit trends.
- Compared sales performance with profit margins to understand differences in profitability.
- Performed correlation analysis on the main numerical variables.
- Identified potential outliers using the IQR method.

## Business Recommendations

- Review products that consistently generate losses and investigate their pricing and discount patterns.
- Monitor high-discount transactions because higher discounts can be associated with lower profitability.
- Focus on products and categories that consistently generate strong profits.
- Analyze regional differences in profitability to identify areas requiring further investigation.
- Use monthly sales and profit trends to support inventory and promotional planning.
- Consider profit margins along with total sales when evaluating business performance.
- Monitor customer segments to understand their contribution to overall profitability.

## Project Structure

superstore-eda/
│
├── data/
│   └── Superstore.csv
│
├── notebooks/
│   └── Superstore_EDA.ipynb
│
├── visualizations/
│
└── README.md