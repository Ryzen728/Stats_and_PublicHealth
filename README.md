# Stats and Public Health
This project analyzes mosquito count and West Nile Virus (WNV) prevalance data from Chicago from the years 2008 to 2019.

## Project Overview
- Public health officials and the public benefit from better understanding the patterns of occurrence of WNV
- The final product included graphs displaying mosquito and WNV patterns.

## Business / Research Problem
- Preventing infection of WNV will eliminate the associated health care costs and preserve life.
- The analysis could direct authorities toward effective WNV prevention strategies.

## Datasets
- Datasets: mosquito_data, mosquito_data_part_2
- 18,495 rows (17,633 after removing duplicates) / 13 columns, data types: int64, float64, object
- Data was made available. The Dataset mosquito_data_part_2 was already cleaned.

## Key Questions / Objectives
- What factors impact the prevalance of mosquitos, differnt mosquito species, and WNV?
- Can we predict the severity of a mosquito or WNV season?
- What are the key trends in effective mosquito trapping?

## Results & Insights
- *Culex restuans* and *Culex pipiens* were the most prevalent mosquito species

## Visualizations
- Graphs of mosquito prevalance by year and by month, respectively, between 2008 and 2019.

## Tools & Technologies
- Python packages (e.g., pandas, numpy, seaborn, matplotlib)

## Methodology
- Data Cleaning & EDA: Counting and removing of missing and duplicate values, visualization of feature variables.
- Feature Engineering: Data resampling to convert raw time stamp data into data organized by month and/or by year.
- Modeling / Analysis: Correlation and cross-correlation analyses between the feature variables and between the feature and target variables. linear and logistic regression models.
- Evaluation: Std err, p-value, correlation coefficient.
