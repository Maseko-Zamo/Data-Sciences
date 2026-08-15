# Data Sciences – Initial Data Exploration

## Project Overview

This project focuses on the **initial exploration and understanding of an HR Employee Attrition dataset** using Python and Pandas.

The purpose of the analysis was to understand the structure of the dataset, identify potential data-quality issues, and explore patterns that may help explain **employee attrition**.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* Vs Code

## Data Exploration (EDA)

The following steps were performed:

* Inspected the first and last rows of the dataset.
* Checked the dataset's shape and structure.
* Reviewed data types using `df.info()`.
* Generated descriptive statistics using `df.describe()`.
* Checked for missing values.
* Checked for duplicate records.
* Explored categorical and numerical variables.
* Created visualisations to identify patterns and trends.
* Analysed the relationship between employee characteristics and attrition.

## Visualisations

The analysis included:

* Histograms to understand the distribution of numerical variables.
* Bar charts to compare categorical variables.
* Pie charts to show proportions.
* Box plots to compare numerical variables across attrition groups.
* Age-group analysis to examine attrition patterns across different age ranges.

## Key Findings

The initial exploration highlighted several useful patterns:

* **Employee attrition is not evenly distributed** across the dataset.
* **Age appears to be an important variable** when examining employee attrition.
* Grouping employees into different age categories makes it easier to identify differences in attrition between younger and older employees.
* Attrition can also be explored across **different departments**, allowing comparisons between areas of the organization.
* Numerical variables such as **income** can be compared between employees who stayed and employees who left.
* Visualisation provides a clearer understanding of patterns that may not be immediately visible from the raw data.

Purpose of the Analysis

The main objective of this initial exploration was to develop an understanding of the dataset before performing more advanced analysis or machine learning.

The findings can help identify potentially important features for future **employee attrition prediction and analysis**.

**Repository Contents**
Data-Sciences/
│
├── Initial Data Exploration.ipynb
├── HR Employee Attrition.xlsx
│
├── Inspection_Report.pdf
├── Inspection_Report.html
│
├── Department Distribution.png
├── Age Distribution.png
├── Attrition Graph.png
├── Attrition Turnover Pie Chart.png
├── Attrition by Age Group.png
├── Attrition by Department.png
├── Attrition vs Overtime Graphs.png
├── Box Plot - Age & Attrition.png
└── Box Plot - Income & Attrition.png

Future Analysis

Future work could include:

* Data cleaning and preprocessing.
* Feature encoding.
* Feature scaling.
* Correlation analysis.
* Further exploratory data analysis.
* Feature selection.
* Machine learning models to predict employee attrition.

Data Science Project – Initial Data Exploration
