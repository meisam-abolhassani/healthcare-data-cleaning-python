# Healthcare Records Cleaning (Python, pandas)

Cleaning a messy patient records file so it can be trusted for reporting.

## Data
`healthcare_raw.xlsx`: a small practice file of 9 patient records with names, visit dates, blood pressure, heart rate, medication, doctor, phone, and email. All records are fictional practice data.

## What the notebook does
* Checks structure and data types, then runs 10 data quality checks
* Standardizes names, gender values, and column names with reusable functions
* Validates ages, heart rate ranges, and blood pressure format; imputes missing blood pressure values
* Validates email and phone formats
* Repairs dates that Excel had corrupted and sorts by visit date
* Exports `Cleaned_Healthcare_Dataset.csv`

## Results
* All 9 defects found were fixed
* Missing values went from 4 to 0
* 3 corrupted dates were recovered

*Tools: Python, pandas, Jupyter. Herzing College coursework, September 2026.*
