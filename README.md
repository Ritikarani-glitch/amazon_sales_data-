# amazon_sales_data-
Project Overview:

This repository contains cleaned versions of raw datasets originally found in archive (1).zip(amazon_sales_data).
The cleaning process was performed using Python (Pandas) to ensure the data is ready for analysis, visualization, or machine learning.
🧠 Objectives:

Ensure data consistency and reliability.
Remove redundant or missing records.
Standardize text, dates, and formats for uniformity.
Prepare the dataset for use in analytical or ML projects.

Tools & Libraries Used:

Python 3.x
Pandas for data manipulation
NumPy for numerical operations
ZIPFILE and OS libraries for file handling


🧼 Data Cleaning Steps
1. Handling Missing Values
Rows containing missing (NaN) values were dropped.
2. Removing Duplicates
All duplicate rows were removed using DataFrame.drop_duplicates().
3. Standardizing Text Values
Whitespace and inconsistent capitalization were removed using str.strip() and str.lower().
Gender and country values were standardized (e.g., “M” → “male”, “India ” → “India”).
4. Formatting Dates
Columns containing “date” were converted to datetime format (dd-mm-yyyy).
5. Cleaning Column Headers
All column names were standardized:
Lowercase text
Spaces replaced with underscores (_)
Special characters removed
6. Fixing Data Types
Numeric columns (like age) were converted to integers.
Date columns were converted to proper datetime objects.

