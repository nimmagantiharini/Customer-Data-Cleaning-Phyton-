# Customer Personality Analysis - Phyton 
## Project Objective
For the Customer Personality Analysis dataset, this repository offers a comprehensive data cleaning methodology.  It contains Python programs to format dates, manage missing numbers, eliminate duplication, standardize text, and correct data types.  The cleaned dataset is ready for additional modeling, analysis, and visualization.
## Data set Used
- <a href="https://github.com/nimmagantiharini/Customer-Data-Cleaning-Phyton-/blob/main/Customer%20personality%20Analysis1.csv"> Raw Dataset of Customer</a>
## Features
- Identify and handle missing values
- Remove duplicate rows
- Standardize text values (e.g., gender, country names)
- Convert date formats to a consistent type (`dd-mm-yyyy`)
- Rename column headers to lowercase, no spaces
- Check and fix data types (e.g., age → int, dates → datetime)
## Structure
customer-data-cleaning/
│── data/
│ └── Customer personality Analysis.csv # raw dataset
│── notebooks/
│ └── data_cleaning.ipynb # Jupyter notebook with cleaning steps
│── scripts/
│ └── clean_data.py # Python script for automated cleaning
│── output/
│ └── Customer_personality_cleaned.csv # cleaned dataset

## Install dependencies:
pip install pandas

## customer-personality-cleaned
- <a href="http://localhost:8888/notebooks/Favorites%2Fharini%2Fcustomers%20data.ipynb"> Customer personality cleaned</a>
## Conclusion
The raw Customer Personality Analysis dataset initially contained missing values, duplicate rows, inconsistent text (e.g., gender, country names), irregular date formats, and incorrect data types. Through systematic cleaning, these issues were resolved by filling missing values, removing duplicates, standardizing text, converting dates to dd-mm-yyyy, renaming columns, and correcting data types. The final dataset (customer-personality-cleaned) is now consistent, structured, and fully prepared for exploratory analysis, visualization, and machine learning applications.
