# Google Advacned Data Analytics Capstone Project

## What I did

The certificate program has tasked me with analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like me to design a model that predicts whether an employee will leave the company based on their  department, number of projects, average monthly hours, and any other data points me deem helpful.

The steps I took were:
- Setup reproducible and versionable python environment, something I learned from my software engineering background
- Familiarize myself with the dataset
- Conduct Exploratory Data Analysis
- Gather descriptive statistics (mean, std, quantiles)
- Cleanup missing and duplicate data
- Check for outliers
- Further examine various relationship between features thru visualization
- Train 3 models using Logistic Regression, DecisionTree and RandomForest
- Compare the performance of the models
- Report my findings

## Result and Work
see `main.ipynb` file.

## About Dataset
sourced from https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv

### Context
Hr Data Analytics
This dataset contains information about employees who worked in a fictitious company.

## Data Dictionary

Variable  |Description |
-----|-----|
satisfaction_level|Employee-reported job satisfaction level [0&ndash;1]|
last_evaluation|Score of employee's last performance review [0&ndash;1]|
number_project|Number of projects employee contributes to|
average_monthly_hours|Average number of hours employee worked per month|
time_spend_company|How long the employee has been with the company (years)
Work_accident|Whether or not the employee experienced an accident while at work
left|Whether or not the employee left the company
promotion_last_5years|Whether or not the employee was promoted in the last 5 years
Department|The employee's department
salary|The employee's salary (U.S. dollars)
