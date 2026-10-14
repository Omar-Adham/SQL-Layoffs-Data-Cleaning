# SQL Data Cleaning Project – Global Layoffs

## Project Overview
This project focuses on cleaning a global layoffs dataset using MySQL. The goal is to prepare raw data for further analysis by removing duplicates, standardizing values, and handling missing information.

## Dataset
Source: [Kaggle – Layoffs 2022](https://www.kaggle.com/datasets/swaptr/layoffs-2022)

## Tools Used
- MySQL
- MySQL Workbench

## Data Cleaning Steps
1. Created staging tables to preserve the original dataset.
2. Identified and removed duplicate records using ROW_NUMBER() and CTEs.
3. Standardized company names, industry categories, and country names.
4. Converted date strings into SQL DATE values.
5. Handled missing industry information using self-joins.
6. Removed records with missing layoff information in both key fields.
7. Removed temporary columns after cleaning.

## SQL Concepts Used
- Window Functions
- Common Table Expressions (CTEs)
- JOINs
- UPDATE and DELETE
- TRIM()
- STR_TO_DATE()
- ALTER TABLE

## Future Improvements
Perform exploratory data analysis to identify trends in layoffs by company, industry, country, and year.
