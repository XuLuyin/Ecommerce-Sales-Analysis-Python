# Ecommerce-Sales-Analysis-Python

This project analyzes a synthetic global e-commerce dataset (2023–2025).
It demonstrates an end-to-end workflow for data cleaning and exploratory data analysis (EDA)
to understand sales trends, customer behavior, and product performance.

## Dataset

- Raw dataset: synthetic_ecommerce_sales_2025.csv
- Fully synthetic, sourced from Kaggle:
  https://www.kaggle.com/datasets/emirhanakku/synthetic-e-commerce-sales-dataset-2025

## Project Structure

01_data_cleaning.ipynb: Clean and preprocess raw data
- Handle missing values and defining data types
- Drop irrelevant columns
- Convert date columns into "year", "month" and "year_month"
- Categorize columns into numerical and categorical types

02_exploratory_analysis.ipynb: Explored the cleaned dataset
- Analyze overall sales trends by year, month, and year-month
- Compare revenue across regions and product categories
- Examine customer behavior: average ratings and return rates
- Visualize insights using Matplotlib and Seaborn
  
cleaned_ecommerce_sales.csv: The cleaned dataset for analysis

## Key Insights

- Revenue shows clear seasonal trends by month, with a noticeable spike in November due to Black Friday.
- Certain product categories and regions consistently outperform others in total sales.
- Return rates vary among regions and product categories. Fashion products clearly have the highest return rates.
- Customer ratings are generally high, with minor variations by regions and product categories.

## Tools
- Programming: Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn
