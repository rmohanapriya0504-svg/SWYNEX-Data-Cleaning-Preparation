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

