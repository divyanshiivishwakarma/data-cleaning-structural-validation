# Data Cleaning & Structural Validation

I worked on a messy customer order dataset and cleaned it using Google Sheets. The goal was to make the data more consistent, reliable, and ready for basic analysis.

## Tools Used

* Google Sheets
* Filters
* Find and Replace
* Basic formulas like `TRIM`, `PROPER`, and `LOWER`
* Manual data validation

## Dataset Overview

The dataset contains customer order details such as order ID, customer name, email, phone number, city, state, order date, product category, quantity, unit price, payment method, delivery status, rating, notes, and total amount.

## What I Cleaned

* Removed duplicate records.
* Cleaned customer names using `TRIM` and `PROPER`.
* Converted email values to a consistent format and marked invalid or missing emails as `Not Available`.
* Standardized phone number formatting.
* Fixed inconsistent city and state names.
* Converted order dates into a consistent date format.
* Standardized product categories.
* Checked quantity and unit price values and kept only valid positive numbers.
* Standardized payment methods and delivery status values.
* Checked ratings and kept only valid values from 1 to 5.
* Added a `Total_Amount` column using `Quantity × Unit_Price`.

## Sheets Included

* `Raw_Data`: Original dataset before cleaning
* `Cleaned_Data`: Working sheet used during the cleaning process
* `Final_Cleaned_Data`: Final cleaned dataset
* `Validation_Summary`: Summary of issues found and actions taken
* `Cleaning_Steps`: Step-by-step cleaning process
* `Data_Dictionary`: Explanation of columns and valid values

## Outcome

The final dataset is cleaner, more consistent, and ready to be used for analysis or dashboard creation.
