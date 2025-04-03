# Cafe Sales Cleaning

This repository contains a Jupyter Notebook containing the processes used to clean a raw café sales dataset using Python and Pandas. The notebook helps identify and fix issues such as missing values, duplicates, and incorrect data types.

## Features
- Loads a raw café sales dataset
- Identifies any possible duplicates
- Addresses Null values
- Standardizes data types
- Provides a clean dataset for further analysis

## Dataset
The dataset consists of several columns containing transaction details from a café. The main columns include:

- `Transaction ID` (unique identifier)
- `Item` (name of sold product)
- `Quantity` (how much of the item was sold)
- `Price Per Unit` (price for each respective item)
- `Total Spent` (cumulative total the customer spent)
- `Payment Method` (the type of payment used)
- `Location` (where item(s) were purchased)
-  `Transaction Date` (date of each transaction)

## Procedures

### Identifying and Removing Duplicates
Duplicate records were checked using the `Transaction ID` column.

### Handling Missing Values
Empty fields were identified in various columns. These missing values were either filled by finding relations with other columns or replaced with appropriate statistical placeholders for better data management.

### Standardizing Data Formats
- Date formats were standardized for consistency.
- Categorical columns remained as objects.
- Numerical columns were converted to floats.

### Finalizing Data Cleaning
Rows with null values that could not be further altered were dropped to improve readability and efficiency.

## Results
The dataset is now well-structured with no null values, no duplicates, and standardized formats, making it ready for further analysis.

## License
This project is licensed under the MIT License.

## Data Source
The dataset used in this notebook was located on Kaggle and can be obtained with the following link: https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training



