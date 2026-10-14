# Employee Data Cleaning and Exploratory Data Analysis

## Project Overview

This project focuses on cleaning, preparing, and analyzing a messy employee dataset using Python. The dataset contains employee information, including employee IDs, names, ages, departments, cities, employment status, monthly salaries, performance scores, hire dates, and email addresses.

The main goal is to transform raw employee data into a clean and consistent dataset that can be used for exploratory data analysis (EDA) and data visualization. The project also uses charts to explore employee demographics, hiring trends, salary differences, and performance scores.

## Project Objectives

- Inspect the dataset to understand its structure, data types, and quality.
- Identify missing values, inconsistent entries, and duplicate records.
- Clean and standardize employee information.
- Convert columns to appropriate data types.
- Handle missing values using suitable methods.
- Save the cleaned dataset as a CSV file.
- Use visualizations to identify patterns and trends in the data.

## Tools and Technologies

The project uses the following Python libraries:

- **Pandas:** Data loading, cleaning, manipulation, grouping, and aggregation.
- **NumPy:** Numerical computing support.
- **Matplotlib:** Creating charts and visualizing employee data.
- **Jupyter Notebook:** Writing and executing Python code in an interactive environment.

## Data Cleaning Process

The data cleaning process includes the following steps:

1. **Data loading:** Import the employee dataset into a Pandas DataFrame.
2. **Data inspection:** Examine column names, data types, missing values, duplicate records, and statistical summaries.
3. **Data type conversion:** Convert employee ages and performance scores to numeric values. Convert hire dates to datetime format.
4. **Missing value treatment:** Replace missing ages and performance scores with their respective medians. Fill missing monthly salaries using department-specific median salaries. Assign the value `unknown` to missing city entries.
5. **Standardization:** Correct inconsistent employment status values, standardize department names, and clean employee names and email addresses.
6. **Column renaming:** Rename the columns using lowercase names and underscores for consistency.
7. **Quality checks:** Examine the number of rows and columns, duplicate records, employee IDs, and email addresses.
8. **Data export:** Save the cleaned dataset as `cleaned_employee_data.csv`.

## Exploratory Data Analysis and Visualizations

The project uses grouping, aggregation, and charts to explore the employee dataset.

- **Employee hires by year:** A bar chart showing the number of employees hired in each year.
- **Employees by department:** A bar chart comparing employee counts across departments.
- **Average monthly salary by department:** A bar chart comparing average salaries across departments.
- **Average performance scores by city:** A bar chart comparing average employee performance scores across cities.
- **Age distribution:** A histogram showing how employee ages are distributed.
- **Salary and performance relationship:** A scatter plot exploring the relationship between monthly salary and performance scores.
- **Employee data by city:** A bar chart intended to examine employee distribution across cities.

## Expected Outcomes

By completing this project, the cleaned dataset becomes more consistent and suitable for analysis. The visualizations help identify hiring patterns, compare departmental salaries, examine employee age distribution, and explore differences in performance scores across cities.

The project also demonstrates practical skills in data cleaning, missing value handling, data type conversion, Pandas groupby operations, statistical aggregation, and data visualization.

## Project Files

- `daMessy Employee Date project.ipynb`: Jupyter Notebook containing the data cleaning and analysis workflow.
- `cleaned_employee_data.csv`: Exported dataset after cleaning.

## Conclusion

This project demonstrates a basic data analysis workflow, from inspecting and cleaning raw data to preparing a dataset for visualization. It provides practical experience in using Python to improve data quality and extract useful information from employee records.
