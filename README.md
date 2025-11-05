# Project Overview
This project performs an Exploratory Data Analysis (EDA) on Adidas sales data to uncover insights into sales performance across regions, products, and customer segments. The goal is to understand key factors driving revenue, highlight sales patterns, and prepare the dataset for potential predictive modeling or business reporting.

# Project Objectives
- Clean and preprocess the Adidas sales dataset for analysis.
- Explore trends across time, regions, retailers, and product categories.
- Identify relationships between sales volume, profit, price, and marketing costs.
- Visualize insights using Python data visualization libraries.

# Data Cleaning Steps

The notebook begins with a thorough data preprocessing phase:

- Extract numeric values from strings (e.g., remove commas, currency symbols, or percentages).
- Convert columns to appropriate data types:
    - int64 for whole numbers
    - float for decimal values
    - datetime for date fields
- Handle missing values by filling or dropping them as appropriate.

# Exploratory Data Analysis (EDA)
The EDA section investigates:
- Sales distribution by region, product, and retailer.
- Revenue and profit trends over time.
- Correlation analysis between sales-related metrics.
- Top-performing products and best regions by revenue contribution.
- Visualizations are built using:
    - matplotlib
    - seaborn
    - pandas plotting functions
