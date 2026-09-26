**SWYNEX - Data Cleaning \& Preparation**
**Project Overview**

This project focuses on cleaning and preparing a raw dataset for analysis.

The dataset contains customer and transaction information, including customer details, transaction amounts, dates, merchant names, and categories.

Dataset Columns

The dataset contains the following columns:

- Customer ID
- Name
- Surname
- Gender
- Birthdate
- Transaction Amount
- Date
- Merchant Name
- Category

**Data Cleaning Performed**

1. Missing Values

Missing values were identified in the dataset.

Missing Gender values were replaced with `Unknown` instead of guessing the original values.

2. Duplicate Records

Duplicate records were checked using all available columns.

Result: No duplicate records were found.

3. Data Type Correction

The following data types and formats were checked and standardized:

- Customer ID was formatted as a whole number without unnecessary decimal places.

- Birthdate was standardized as a date.

- Transaction Amount was formatted as a numeric value with two decimal places.

- Date was standardized as a date.

- Text fields were checked for consistency.

4. Inconsistent Values

Inconsistent Gender values were identified.

The value `unknow` was corrected to `Unknown`.

The Category column was checked and found to contain consistently formatted values.

Merchant Name values were also reviewed for obvious inconsistencies.

Files Included

- raw_data.xlsx - Original raw dataset.

- cleaned_data.xlsx - Cleaned and prepared dataset.

- README.md - Documentation of the cleaning process.

Conclusion

The dataset was cleaned and prepared for further analysis by handling missing values, checking duplicate records, correcting data formats, and standardizing inconsistent values.


## Task 2 - Exploratory Data Analysis (EDA)

### Objective

The objective of Task 2 is to perform exploratory data analysis on the cleaned dataset from Task 1. The analysis was performed using Microsoft Excel to calculate important statistics, identify trends, patterns, and anomalies, and create meaningful visualizations.

### Analysis Performed

- Calculated total number of transactions.
- Calculated total transaction amount.
- Calculated average transaction amount.
- Identified the highest and lowest transaction amounts.
- Analyzed high-value transactions above 2,000.
- Performed gender-wise transaction analysis.
- Analyzed transactions by category.
- Analyzed monthly transaction amount trends.
- Checked for unusual, negative, and zero transaction values.
- Created charts and visualizations to understand the data.

### Key Statistics

- **Total Transactions:** 50,000
- **Total Transaction Amount:** Approximately 22.11 million
- **Average Transaction Amount:** Approximately 442
- **Lowest Transaction Amount:** 5.01
- **Highest Transaction Amount:** 2,999.88
- **High-Value Transactions above 2,000:** 2,845

### 5 Useful Insights

1. The dataset contains **50,000 transactions**.
2. The total transaction amount is approximately **22.11 million**.
3. The average transaction amount is approximately **442**.
4. Transaction amounts range from **5.01 to 2,999.88**.
5. There are **2,845 high-value transactions above 2,000**.

### Anomaly Analysis

- No negative transaction values were identified.
- No zero transaction values were identified.
- No obvious unusual high or low transaction values were identified.

### Task 2 File

The complete exploratory data analysis is available in:

**Task_2_EDA_Analysis.xlsx**
