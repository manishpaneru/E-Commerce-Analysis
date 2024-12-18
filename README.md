# E-Commerce Data Analysis

This repository contains a comprehensive analysis of e-commerce data using Python and Jupyter Notebook. The analysis explores various aspects of the business including sales trends, customer demographics, product performance, and revenue drivers.

## Project Overview

The project analyzes an e-commerce dataset (`data.csv`) containing information about:
- Customer demographics (ID, Gender, Region, Age)
- Product details (Name, Category, Unit Price)
- Order information (Quantity, Total Price, Shipping Fee, Order Date)
- Shipping status

## Analysis Components

The Jupyter notebook (`EDA.ipynb`) includes:
1. Data Quality Assessment
   - Missing value analysis
   - Data distribution checks

2. Revenue Analysis
   - Temporal revenue trends
   - Peak and off-peak revenue periods
   - Revenue drivers correlation analysis

3. Product Performance Analysis
   - Top-performing products and categories
   - Price range analysis
   - Unit price distribution

4. Customer Demographics Analysis
   - Gender and region distribution
   - Age group analysis
   - Purchase patterns

5. Visualizations
   - Time series plots
   - Correlation heatmaps
   - Distribution charts
   - Category-wise performance graphs

## Requirements

To run the analysis, you'll need:
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib

## Setup Instructions

1. Clone this repository
2. Install the required packages:
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
3. Open `EDA.ipynb` in Jupyter Notebook or Jupyter Lab
4. Run the cells sequentially to reproduce the analysis

## Data

The analysis uses `data.csv`, which contains 1000 rows of e-commerce transaction data. Note that some fields (Region, Age, Shipping Status) contain missing values that are handled in the analysis.

## License

This project is licensed under the terms included in the LICENSE file. 