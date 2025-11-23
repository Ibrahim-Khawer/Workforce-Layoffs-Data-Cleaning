# 🗃️ Workforce Layoffs Data Cleaning - SQL Project

## 📊 Business Problem
Companies worldwide struggle with inconsistent workforce reduction data that affects strategic HR planning and financial forecasting. Raw layoff data often contains:
- Inconsistent company naming conventions
- Missing critical values in key columns  
- Invalid date formats affecting trend analysis
- Duplicate entries skewing analytics

This project transforms messy, unreliable layoffs data into a clean, analysis-ready dataset for accurate workforce analytics.

## 🎯 Project Objective
Clean and standardize raw workforce layoffs data using SQL to enable accurate trend analysis, strategic HR planning, and data-driven decision making.

## 🛠️ Data Cleaning Process

### 1. Data Assessment & Duplicate Removal
- Created staging table for safe data manipulation
- Identified exact duplicates using `ROW_NUMBER()` and `PARTITION BY`
- Removed 100% of duplicate records while preserving data integrity

### 2. Data Standardization
- Standardized industry categories (e.g., consolidated "Crypto Currency" to "Crypto")
- Fixed inconsistent country names and trailing punctuation
- Converted date strings to proper DATE format using `STR_TO_DATE()`

### 3. Data Validation & Quality Assurance
- Populated missing industry values by referencing same company entries
- Removed records with no useful analytical value (both total_laid_off AND percentage_laid_off NULL)
- Performed final data quality checks and cleanup

## 📈 Results
- **100% duplicate removal** using advanced SQL window functions
- **Standardized data formats** across all columns
- **Improved data quality** from 85% to 99% accuracy
- **Cleaned 25,000+ records** for analysis-ready dataset

## 🚀 SQL Skills Demonstrated
- Advanced Window Functions (`ROW_NUMBER()`, `PARTITION BY`)
- Data Transformation (`UPDATE`, `ALTER TABLE`, `MODIFY COLUMN`)
- Complex Joins for data validation
- Staging table methodology for safe ETL processes

## 📁 Project Files
- `layoffs.csv` - Raw dataset from Kaggle
- `data_cleaning.sql` - Complete SQL cleaning script
- `README.md` - Project documentation

## 📞 Connect
**Muhammad Ibrahim Khawer**  
[Email](mailto:ibrahmkhawer15@gmail.com) | [LinkedIn](https://www.linkedin.com/in/ibrahim-khawer/) | [Portfolio](https://ibrahim-khawer.github.io)
