# Retail Sales and Inventory Management Data Engineering Project

## Overview

This project simulates a retail environment to generate synthetic sales, customer, and inventory data. The goal is to create a data engineering pipeline that ingests, processes, stores, and analyzes the data, providing insights for optimizing inventory management and sales forecasting.

## Project Structure

- **customer_data.csv**: Contains synthetic data for 20 customers, including demographic information and customer segments.
- **inventory_data.csv**: Contains synthetic data for 20 products, including inventory levels, restock dates, supplier IDs, and pricing information.
- **sales_data.csv**: Contains 100 synthetic sales transactions, each linked to a customer and a product from the above datasets.

## Data Generation

The data was generated using Python and the Faker library, with an emphasis on creating realistic and repeatable customer and product interactions. The generated sales data references a consistent set of customers and products, allowing for meaningful analysis of sales trends, inventory levels, and customer behavior.

## Visualizations

To support inventory management and sales forecasting, four key visualizations are recommended:

1. **Sales vs. Inventory Levels Over Time (Line Chart)**
   - **Purpose**: Track the relationship between sales and inventory levels over time to identify trends and potential issues like stockouts or overstock situations.
   - **Implementation**: Dual-axis line chart with sales on one axis and inventory levels on the other.

2. **ABC Analysis (Bar Chart)**
   - **Purpose**: Categorize inventory into A, B, and C categories based on importance (e.g., sales value), helping to prioritize inventory management efforts.
   - **Implementation**: Bar chart displaying cumulative sales or value by product, highlighting A, B, and C categories.

3. **Inventory Heatmap (Heatmap)**
   - **Purpose**: Visualize inventory levels across different products and time periods, making it easy to spot periods of high or low inventory.
   - **Implementation**: Heatmap with time on the x-axis and products on the y-axis, where color intensity represents stock levels.

4. **Sales Forecasting (Time Series with Confidence Intervals)**
   - **Purpose**: Predict future sales based on historical data, helping to prepare for demand fluctuations and adjust inventory levels.
   - **Implementation**: Time series plot with a forecast line and confidence intervals.

## How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/retail-sales-inventory.git
   cd retail-sales-inventory
