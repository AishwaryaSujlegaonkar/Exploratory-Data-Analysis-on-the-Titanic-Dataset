# Exploratory-Data-Analysis-on-the-Titanic-Dataset
Project Overview : This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset from Kaggle. The main goal is to uncover patterns, trends, and correlations within the dataset—especially related to passenger demographics and survival rates.

Problem Statement : The objective is to analyze the Titanic dataset to gain insights about Passenger demographics (age, gender, class), Survival patterns and correlations, Relationships among various features.

Skills Applied : Data Wrangling and Cleaning, Data Visualization with Seaborn and Matplotlib, Feature Engineering and Insights Extraction, Reporting and EDA Documentation

Tools & Technologies : Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
Dataset : Kaggle Titanic Dataset

EDA Workflow :
1. Data Loading & Inspection
Loaded data into a Pandas DataFrame
Checked structure, types, and sample entries

2. Data Cleaning
Handled missing values (Age, Cabin, Embarked)
Removed duplicates
Converted categorical data types

3. Univariate Analysis
Count plots for Survived, Sex, Pclass, Embarked
Distribution plots for Age and Fare

4. Bivariate Analysis
Survival comparison by Sex, Pclass
Scatter plot for Age vs Fare

5. Multivariate Analysis
Heatmap of correlations
Survival analysis based on Sex and Pclass

6. Feature Engineering
Extracted Title from names
Created Fare Ranges
Calculated Family Size
Analyzed impact on survival

7. Key Insights
Females had higher survival rates than males
First-class passengers had a higher chance of survival
Family size and title influenced survival probability
