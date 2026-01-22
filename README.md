<img width="275" height="183" alt="images" src="https://github.com/user-attachments/assets/0e5bd695-3be4-48e0-a4b4-0d74d14fdcf7" />


# Data Cleaning & Preprocessing [ Titanic Data]
## Project Overview
This project demonstrates a complete data cleaning and preprocessing workflow using Python.
The goal was to transform raw, inconsistent data into a structured, analysis-ready dataset
suitable for downstream analytics and dashboarding.
## Dataset
- Source: [https://drive.google.com/file/d/1Uw7RzQMYSARCFnzJQqqNlZpUouXr16-8/view]
- Rows: 906
- Columns: 13
- - Common issues:
  - Missing values
  - Duplicate records
  - Inconsistent date formats
  - Outliers in numerical fields
## Tools & Technologies
- Python
- Pandas
- NumPy
- Google Notebook
  ## Data Cleaning Process

1. Data Inspection
   - Checked data types and structure
   - Identified missing and invalid values

2. Handling Missing Values
   - Removed rows with critical missing fields
   - Imputed numerical columns using median

3. Removing Duplicates
   - Identified duplicate records based on primary keys
   - Removed 15 duplicate rows

4. Data Type Standardization
   - Converted date columns to datetime format
   - Ensured numerical fields were correctly typed

5. Outlier Treatment
   - Detected extreme values using IQR method
   - Capped outliers to reduce skewness

6. Final Validation
   - Verified row counts and summary statistics
     ## Key Outcomes
- Reduced missing values by 30%
- Removed 15 duplicate records
- Produced a clean dataset ready for analysis and visualization
- Exported cleaned dataset

