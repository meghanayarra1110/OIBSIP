# Retail Sales Data Analysis – Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset using Python. The analysis focuses on understanding sales trends, customer demographics, product category performance, and purchasing behavior.

The dataset contains 1,000 retail transactions with information such as transaction date, gender, age, product category, quantity, price per unit, and total transaction amount.

## Objectives

- Understand the structure and quality of the retail sales dataset.
- Perform descriptive statistical analysis.
- Analyze monthly and quarterly sales trends.
- Examine customer demographics based on age and gender.
- Analyze product category performance.
- Identify relationships between numerical variables.
- Compare average transaction values across age groups.
- Generate business insights from the analysis.

## Steps Performed

1. Loaded the retail sales dataset using Pandas.
2. Inspected the dataset structure, data types, missing values, and duplicate records.
3. Converted the transaction date into a proper datetime format.
4. Calculated descriptive statistics such as mean, median, mode, and standard deviation.
5. Analyzed monthly and quarterly sales trends.
6. Created customer age groups and analyzed customer distribution.
7. Analyzed customer distribution and sales by gender.
8. Analyzed product categories based on quantity, revenue, and number of transactions.
9. Created a correlation heatmap for numerical variables.
10. Compared average transaction values across different age groups.
11. Generated visualizations and interpreted the results.
12. Provided business recommendations based on the findings.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Key Findings

- The dataset contains 1,000 retail transactions.
- Sales performance varies across different months and quarters.
- Customer purchasing behavior differs across age groups and genders.
- Product categories contribute differently to total quantity sold and revenue.
- Average transaction values vary across age groups.
- In this dataset, the Below 20 age group has the highest average transaction value.

## Dataset Limitation

The dataset contains product categories rather than individual product names. Therefore, an individual top-10 product analysis could not be performed without introducing information that is not present in the dataset. Category-level quantity and revenue analysis was used instead.

## Outcome

The analysis provides an overview of retail sales performance, customer demographics, product category contribution, and purchasing behavior. The insights can support decisions related to marketing, inventory planning, and promotional strategies.

## Project Files

- `Retail_Sales_EDA.ipynb` – Complete analysis notebook
- `retail_sales_dataset.csv` – Dataset used for the analysis
- `README.md` – Project documentation

## Internship

This project was completed as part of the **Oasis Infobyte Internship Program – Data Analytics Track**.
