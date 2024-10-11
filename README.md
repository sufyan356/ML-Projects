## Insurance Claim Analysis Project

## Project Overview

This project focuses on performing data cleaning, exploratory data analysis (EDA), and feature engineering on an insurance dataset to derive valuable insights and trends. The goal is to analyze the behavior of different groups, such as males vs. females, smokers vs. non-smokers, and various regions, with respect to their insurance claim rates. The dataset includes features such as gender, age, BMI, blood pressure, smoker status, diabetic status, and the target variable, claim.

## Dataset: https://www.kaggle.com/datasets/thedevastator/insurance-claim-analysis-demographic-and-health.
## The dataset used in this project contains the following columns:

PatientID: Unique identifier for each patient
age: Age of the patient
gender: Gender of the patient (male/female)
bmi: Body Mass Index of the patient
bloodpressure: Blood pressure reading (single value)
diabetic: Diabetic status (yes/no)
children: Number of children
smoker: Smoking status (yes/no)
region: Geographic region (e.g., Northeast, Southeast, Northwest)
claim: Insurance claim amount (target variable)
bloodpressure_category: Feature-engineered column that categorizes blood pressure values (low, normal, elevated, hypertension)

## Project Goals:

Perform data cleaning to handle missing values, inconsistent entries, and ensure data quality.
Conduct exploratory data analysis (EDA) to discover patterns and trends.
Use feature engineering to transform or create new features such as categorizing BMI and blood pressure.
Visualize bivariate relationships between the target column (claim) and other features.

## Project Goals:

Perform data cleaning to handle missing values, inconsistent entries, and ensure data quality.
Conduct exploratory data analysis (EDA) to discover patterns and trends.
Use feature engineering to transform or create new features such as categorizing BMI and blood pressure.
Visualize bivariate relationships between the target column (claim) and other features.
Derive insights and conclusions based on the analysis to understand claim behavior better.

## Methodology:

## 1. Data Cleaning
Handled missing values and ensured all data types were appropriate for analysis.
Created new categorical features such as bloodpressure_category to enhance analysis.

## 2. Exploratory Data Analysis (EDA):
Analyzed numerical and categorical features.
Performed univariate, bivariate, and multivariate analysis to uncover trends.
Created various visualizations such as box plots, violin plots, KDE plots, and scatter plots.

## 3. Feature Engineering:
Created blood pressure categories (low, normal, elevated, hypertension1, hypertension2) based on numeric values.

## 4. Visualization Techniques:
Violin Plots: To compare the distribution of claims by gender and smoker status.
Box Plots: To examine the range and outliers of claims for different groups.
Scatter Plots: For visualizing relationships between continuous variables.
KDE Plots: To understand the density distribution of claims by category.

## Key Insights:

Males generally claim insurance at a slightly higher rate than females, though the difference is not significant.
Smokers have a significantly higher claim rate compared to non-smokers.
The Northeast region shows the highest insurance claim rates, while the Northwest region shows the lowest.
Smokers claim insurance at almost equal rates for both males and females.

## Conclusion:

Through this analysis, it was found that smoker status, region, and gender play important roles in insurance claim rates. Smokers, particularly in the Northeast region, are more likely to claim higher amounts of insurance. Diabetic and non-diabetic patients tend to have similar smoking rates, and blood pressure levels show that most patients fall within normal ranges.

## How to Use?
## To replicate this analysis:

Clone this repository.
Install the required libraries: pandas, numpy, matplotlib, seaborn.
Load the dataset and run the provided Jupyter notebook or Python scripts for analysis.

## Technologies Used:

Python: For data manipulation and analysis.
Pandas: For data wrangling and preprocessing.
Matplotlib & Seaborn: For data visualization.
NumPy: For numerical operations.

## Future Work:
Explore predictive modeling techniques to predict insurance claims based on patient features.
Further optimize feature engineering for more granular insights.
A majority of patients with normal blood pressure levels exist, while very few have extremely high blood pressure.
Derive insights and conclusions based on the analysis to understand claim behavior better.
