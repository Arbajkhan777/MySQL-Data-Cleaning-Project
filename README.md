# Layoffs Data Cleaning and Analysis (2022)

This project involves cleaning and analyzing a dataset of layoffs in 2022. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022) and includes information on various companies, the number of employees laid off, industry, and other related data.

## 🔥 Project Overview
The goal of this project is two-fold:
1. **Data Cleaning**: Remove duplicates, standardize data, handle missing values, and fix any inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Analyze the data to gain insights into layoffs across different companies and industries.

---

## 📁 Files in This Repository
- **`layoffs.csv`**: The original dataset containing layoffs data for 2022.
- **`layoffs_data_cleaning.sql`**: SQL script for cleaning the dataset (handling duplicates, standardizing values, fixing nulls, etc.).
- **`EDA.sql`**: SQL script for performing exploratory data analysis on the cleaned dataset.
- **`layoffs_cleaned.csv`**: The final cleaned dataset after performing cleaning steps.

---

## 📄 Data Cleaning Steps
- **Created a staging table** to preserve raw data and work on a separate table for cleaning.
- **Removed duplicates** by identifying and deleting repeated rows using a combination of columns (company, industry, date, etc.).
- **Standardized columns**: Trimmed unnecessary spaces, standardized industry names (e.g., “Crypto” for all cryptocurrency companies), and converted date formats.
- **Handled missing values** by either filling them using data from related rows or removing incomplete rows.

---

## 📊 Exploratory Data Analysis (EDA)
The following analyses were performed:
- **Layoff Percentages**: Examined the percentage of layoffs across different companies, including companies that had 100% of their workforce laid off.
- **Company Size vs. Layoffs**: Analyzed companies’ funding (`funds_raised_millions`) and their corresponding layoffs.
- **Biggest Single Layoffs**: Identified companies with the largest single layoffs.
- **Total Layoffs by Company**: Analyzed which companies had the most layoffs overall.
- **Yearly Layoffs**: Explored total layoffs per year to understand trends over time.
- **Rolling Total of Layoffs**: Calculated the rolling total of layoffs per month for a more dynamic analysis of the data.

---

## How to Use
1. Download the dataset from Kaggle or use the provided `layoffs.csv`.
2. Run the SQL scripts (`layoffs_data_cleaning.sql` and `EDA.sql`) in a MySQL-compatible environment to clean and analyze the data.
3. Review the results to gain insights into layoffs across industries and companies in 2022.

---

## Dataset Source
The dataset is available on Kaggle: [Layoffs 2022 Dataset](https://www.kaggle.com/datasets/swaptr/layoffs-2022).

---
## Contact

For any questions or feedback, feel free to reach out at arbajkhan2117@gmail.com.
