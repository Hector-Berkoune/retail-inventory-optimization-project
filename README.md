# Retail Inventory Optimization Using Demand Forecasting and Data Analytics

## Project Overview

Retail companies often struggle to balance inventory levels. Overstocking increases storage costs, while understocking may lead to lost sales.

This project analyzes historical retail sales and inventory data to identify trends, evaluate inventory performance, and examine forecasted product demand.

Python was used for data cleaning, analysis, and machine learning. Power BI was used to create an interactive three-page dashboard.

## Business Problem

Retail businesses need to maintain enough inventory to meet demand without holding unnecessary stock.

The objectives of this project were to:

- Analyze sales and revenue performance
- Evaluate inventory levels
- Identify high-performing products
- Examine historical monthly demand patterns
- Support inventory replenishment decisions

## Dataset

The dataset contains approximately 73,100 records and includes:

- Sales dates
- Store and product identifiers
- Product categories
- Regions
- Inventory levels
- Units sold
- Units ordered
- Demand forecasts
- Prices
- Discounts
- Weather conditions
- Promotions
- Competitor pricing
- Seasonality

The analysis covers data from January 2022 through January 2024.

Product IDs are reused across categories. Therefore, product-level analysis uses the combination of Product Category and Product ID.

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Power BI
- Excel

## Project Workflow

### Data Cleaning

- Checked missing values
- Checked duplicate records
- Validated numerical values
- Standardized analytical fields
- Created additional date and revenue variables

### Exploratory Data Analysis

The analysis examined:

- Total revenue
- Total units sold
- Monthly sales trends
- Revenue by category
- Revenue by region
- Product performance
- Inventory levels

### Inventory Analysis

The project included:

- Inventory turnover analysis
- ABC product classification
- Inventory comparison by category and region
- Inventory level versus units sold analysis

### Demand Forecasting

A Random Forest Regression model was developed to predict units sold.

Model results:

- MAE: 69.63
- RMSE: 89.32
- R²: 0.326

## Power BI Dashboard

The dashboard contains three pages.

### Executive Dashboard

Provides an overview of:

- Total revenue
- Total units sold
- Average inventory level
- Revenue by category
- Monthly revenue trend
- Revenue by region
- Top products by revenue

### Inventory Analysis

Includes:

- Average inventory level
- Average demand forecast
- Inventory by category
- Inventory by region
- Inventory level versus units sold
- Top products by inventory level
- Inventory details table

### Demand Forecast and Recommendations

Includes:

- Historical monthly demand forecast
- Two-year demand forecast heatmap
- Top products by forecasted demand
- Forecast details
- Business recommendations

## Key Findings

- Furniture generated the highest total revenue, although revenue was relatively balanced across categories.
- Regional revenue performance was also relatively balanced.
- Historical monthly demand patterns were stronger during January, March, July, and October.
- Product-level performance differences were greater than category-level differences.
- Some products maintained similar inventory levels while producing different sales results.
- Inventory decisions should therefore be made primarily at the product and month level.
