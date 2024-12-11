# Sales Analysis and Forecasting Project

## Overview
The **Sales Analysis and Forecasting Project** is designed to analyze sales data from various products and predict future sales trends. This repository provides a comprehensive set of tools for data preprocessing, analysis, visualization, and forecasting, enabling businesses to make data-driven decisions.

## Features
- **Data Cleaning**: Handles missing values, type casting, and date parsing to ensure data integrity.
- **Sales Visualization**: Generates insightful plots to visualize total sales, quantity sold, and customer purchase frequency.
- **Customer Segmentation**: Analyzes customer purchase behavior and segments them based on purchase frequency using K-Means and DBSCAN clustering methods.
- **Sales Trend Analysis**: Examines sales trends over time, providing insights into monthly sales performance.
- **Forecasting Models**: Implements time series forecasting techniques using Prophet by Meta and SARIMA to predict future sales.

## Requirements
This project is built using Python, specifically in a Jupyter Notebook environment (version 3.11.7), and utilizes several libraries, including:
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Seaborn**: For enhanced data visualization.
- **Prophet**: For time series forecasting.
- **Statsmodels**: For SARIMA modeling.
- **Scikit-learn**: For clustering and metrics evaluation.

## Dataset
The used dataset consists of sales records from January to June 2024, including:
- **Invoice Date**: The date of each transaction.
- **Product Code**: Unique identifier for each product.
- **Product Name**: Name of the product sold.
- **Net Amount**: The net sales amount for each transaction.
- **Quantity Sold**: The number of units sold in each transaction.

## Analysis Steps
1. **Data Preprocessing**: Clean and prepare the data for analysis by removing unnecessary entries and converting date formats.
2. **Sales Summary**: Aggregate sales data by product to calculate total sales, transaction counts, and quantities sold.
3. **Visualization**: Create bar charts to visualize total sales and quantities sold per product, as well as customer purchase frequency.
4. **Customer Segmentation**: Segment customers based on their purchase frequency to identify loyal customers and those needing engagement using K-Means and DBSCAN clustering methods.
5. **Sales Trend Analysis**: Analyze sales trends over time to understand seasonal patterns and overall performance.
6. **Correlation Analysis**: Examine the relationship between net sales and quantity sold using correlation metrics and visualizations.
7. **Forecasting**: Use the Prophet model and SARIMA to predict future sales based on historical data, providing insights for inventory and marketing strategies.

## Conclusion
The goal of this project is to provide a detailed analysis of sales data, helping businesses understand their performance and customer behavior. By leveraging forecasting techniques, businesses can better prepare for future demand, optimize inventory, and enhance marketing strategies. The insights gained from this analysis can lead to improved customer satisfaction and increased sales.

## Performance Metrics
- **Prophet Model**: 
  - Mean Absolute Error (MAE): 31,219,104.96
  - Mean Absolute Percentage Error (MAPE): 83.64%
  
- **SARIMA Model**: 
  - Mean Absolute Error (MAE): 27,206,261.69
  - Mean Absolute Percentage Error (MAPE): 88.76%
