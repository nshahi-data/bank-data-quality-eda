# Bank Data Quality & Exploratory Data Analysis

## Project Overview

This project demonstrates practical data quality validation and exploratory data analysis (EDA) on a sample banking customer dataset using Python and Pandas.

The objective is to identify common data quality issues that can occur when data moves between enterprise systems, such as missing values, incorrect data types, invalid dates, inconsistent values, and business-rule violations.

The project is based on data-quality scenarios commonly encountered in banking and enterprise data environments.

## Business Problem

Banking data used for reporting, analytics, migration, and downstream applications must be validated before it can be trusted.

Typical issues include:

- Missing mandatory customer information
- Incorrect or inconsistent data types
- Invalid date values
- Missing credit scores
- Incorrect email formats
- Unexpected or invalid business values
- Data inconsistencies that can affect downstream processing

This project demonstrates how Python can be used to systematically profile and validate such data.

## Dataset

The project uses a small synthetic banking customer dataset created for demonstration purposes.

The dataset contains fields such as:

- Customer ID
- Customer Name
- Nationality
- Branch
- Customer Segment
- Account Type
- Balance
- Annual Income
- Credit Score
- Email
- Join Date
- Last Transaction Date

No real customer or confidential banking data is used.

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook / Google Colab
- GitHub

## Data Quality Checks

The notebook currently demonstrates:

- Initial data loading and profiling
- Dataset structure and datatype inspection
- Missing-value identification
- Basic statistical profiling
- Date conversion and validation
- Detection of invalid date values
- Initial business-rule validation

Additional validation and EDA checks will be added as the project progresses.

## Project Structure

    bank-data-quality-eda/
    |
    ├── notebooks/
    │   └── 01_data_loading_and_profiling.ipynb
    |
    └── README.md

## Key Learnings

This project reinforces an important principle of enterprise data engineering:

**Data should be profiled and validated before it is used for analytics or downstream processing.**

Rather than immediately correcting every anomaly, the first step is to understand the data, identify quality issues, and determine which values represent genuine errors versus valid business scenarios.

## Future Improvements

Planned additions include:

- More business-rule validations
- Email validation
- Credit-score validation
- Duplicate analysis
- Outlier analysis
- Data-cleaning strategy
- Exploratory visualizations
- Data-quality summary reporting
