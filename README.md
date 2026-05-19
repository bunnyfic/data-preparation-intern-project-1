# data-preparation-intern-project-1
Week 1 virtual internship project focused on data cleaning, validation, and preparation using Python and Excel.

# Data Cleaning & Preparation Project

## Overview
This project focuses on data cleaning and preparation using Python, Pandas, and Excel. The dataset contains ecommerce transaction data and was cleaned to improve consistency, accuracy, and reliability before analysis.

---

## Objectives
- Handle missing values
- Validate duplicate records
- Standardize text and date formats
- Verify pricing consistency
- Detect potential outliers
- Document all preprocessing steps

---

## Tools & Technologies
- Python
- Pandas
- Jupyter Notebook
- Excel
- ReportLab

---

## Data Cleaning Steps

### 1. Missing Value Handling
- Identified missing values using Pandas
- Filled missing `CouponCode` values with `"No Coupon"`

### 2. Duplicate Validation
- Checked for duplicate rows
- Verified uniqueness of `OrderID`

### 3. Text Standardization
- Removed extra spaces
- Standardized capitalization formatting

### 4. Data Validation
- Validated quantity values
- Verified:
  Quantity × UnitPrice = TotalPrice

### 5. Outlier Detection
- Applied IQR method to identify extreme transaction values
- Retained valid business outliers after verification

---

## Project Files

| File | Description |
|------|-------------|
| `Dataset for Data Analytics.xlsx` | Original dataset |
| `Final_Cleaned_Project.xlsx` | Cleaned dataset with summary sheets |
| `Change_Log.pdf` | PDF documentation of preprocessing steps |
| `Data_Cleaning.ipynb` | Jupyter Notebook containing Python workflow |

---

## Key Outcomes
- Improved dataset consistency
- Preserved data integrity
- Created reproducible preprocessing workflow
- Documented all cleaning operations

---

## Author
Maya
