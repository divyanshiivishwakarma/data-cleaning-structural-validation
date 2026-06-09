# Data Cleaning & Structural Validation

## Task Objective

The objective of this task was to clean a messy customer order dataset and convert it into a structured, accurate, and analysis-ready format.

## Tools Used

* Google Sheets
* Data Cleaning
* Structural Validation
* Basic Formulas
* Filters
* Find and Replace

## Dataset Overview

The dataset contains customer order information such as order ID, customer details, city, state, order date, product category, quantity, unit price, payment method, delivery status, rating, notes, and total amount.

## Work Performed

* Preserved the original dataset in the `Raw_Data` sheet.
* Created a working cleaned dataset in the `Cleaned_Data` sheet.
* Created a final cleaned version in the `Final_Cleaned_Data` sheet.
* Removed duplicate records.
* Cleaned customer names using `TRIM` and `PROPER` formatting.
* Standardized email values and marked invalid or missing emails as `Not Available`.
* Standardized phone number formatting.
* Corrected inconsistent city and state names.
* Standardized order dates into a consistent date format.
* Cleaned and standardized product category names.
* Validated quantity values and kept only valid quantities greater than 0.
* Cleaned unit prices and kept only valid prices greater than 0.
* Standardized payment method names.
* Standardized delivery status values.
* Checked customer ratings and kept only valid ratings from 1 to 5.
* Added a `Total_Amount` column using `Quantity × Unit_Price`.
* Created `Validation_Summary`, `Cleaning_Steps`, and `Data_Dictionary` sheets to document the cleaning process.

## Sheets Included

* `Raw_Data`: Original unedited dataset
* `Cleaned_Data`: Working cleaned dataset
* `Final_Cleaned_Data`: Final cleaned dataset ready for analysis
* `Validation_Summary`: Summary of issues found and actions taken
* `Cleaning_Steps`: Step-by-step cleaning process
* `Data_Dictionary`: Explanation of each column and valid values

## Outcome

The raw dataset was cleaned, standardized, validated, and prepared for further analysis, and dashboard creation.
