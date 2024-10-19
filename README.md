# Sales Data Analysis & Forecasting

## Project Overview

This project involves **Sales Data Analysis and Forecasting** for a grocery shop using Python. The objective of this project is to analyze historical sales data, identify trends, and forecast future sales based on past performance.

The analysis focuses on:
- Understanding the **sales trends** over time.
- Identifying **key sales drivers**.
- Finding **loss-making products**.
- Using forecasting techniques to predict future sales.

## Dataset

The dataset contains sales records from a grocery shop, including the following fields:
- **Order ID**: Unique identifier for each order.
- **Order Date**: Date when the order was placed.
- **Ship Date**: Date when the order was shipped.
- **Ship Mode**: Delivery method (e.g., Standard Class, Second Class).
- **Customer ID**: Unique identifier for each customer.
- **Customer Name**: Name of the customer.
- **Segment**: Customer segment (e.g., Consumer, Corporate).
- **Country/City/State/Region**: Geographic information about the order.
- **Product ID**: Unique identifier for the product.
- **Category/Sub-Category**: Product classification.
- **Product Name**: The name of the product.
- **Sales**: The total sales amount for the order.

## Steps Involved

### 1. Data Preprocessing
- **Loading Data**: The data is loaded using **pandas**.
- **Data Cleaning**: Checked for missing values and handled them appropriately.
- **Date Formatting**: Converted the order and shipment dates to the proper date-time format.
- **Feature Engineering**: Extracted additional features such as sales month and year for better analysis.

### 2. Exploratory Data Analysis (EDA)
- **Sales Trend Analysis**: Visualized sales trends over time to identify seasonality or patterns.
- **Top and Bottom Products**: Identified the top 10 best-selling and loss-making products based on sales data.
- **Sales by Segment and Region**: Analyzed sales by customer segment and geographic region to understand performance variations.
- **Ship Mode Performance**: Analyzed the impact of different shipping modes on sales.

### 3. Sales Forecasting
- Using **time series analysis**, I forecasted future sales based on historical data.
  - **Moving Averages**: Applied simple moving averages to smooth out the sales trend.
  - **ARIMA Model**: Implemented the ARIMA model to predict future sales based on past data.

### 4. Visualization
- Created visualizations using **matplotlib** and **seaborn** to illustrate:
  - Monthly and yearly sales trends (line charts).
  - Top and bottom products (bar charts).
  - Sales breakdown by category and region.

### 5. Identifying Loss-Making Products
- Calculated the total sales per product and identified the **top 10 products** with the lowest sales as loss-making products.

## Tools & Technologies Used
- **Python**: The primary language used for data analysis.
- **pandas**: For data manipulation and cleaning.
- **matplotlib & seaborn**: For data visualization.
- **NumPy**: For numerical operations.
- **ARIMA**: For time series forecasting.

## Project Setup and Execution

### 1. Clone the repository

```bash
git clone https://github.com/your-username/sales-data-analysis-forecasting.git
cd sales-data-analysis-forecasting
