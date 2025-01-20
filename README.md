# Titanic Dataset Analysis Project

## Overview
This project focuses on analyzing the Titanic dataset to understand various factors that influenced passenger survival rates during the Titanic disaster. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization of key patterns and relationships in the data.

## Dataset Description
The Titanic dataset contains information about passengers including:
- Survival status
- Passenger class (Pclass)
- Name
- Sex
- Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Ticket number
- Fare
- Cabin number
- Port of embarkation

## Project Structure
1. Data Loading and Initial Exploration
   - Loading required libraries
   - Importing the dataset
   - Initial data overview

2. Data Cleaning
   - Handling missing values
   - Creating new features (Family_size)
   - Removing unnecessary columns

3. Exploratory Data Analysis
   - Analysis of missing values using heatmap
   - Distribution analysis of numerical variables
   - Correlation analysis
   - Survival rate analysis based on different features

4. Visualizations
   - Histograms for numerical variables
   - Bar plots for categorical variables
   - Correlation heatmaps
   - Family size distribution and its relation to survival

## Key Findings
- Family size appears to have an impact on survival rates
- Missing values were primarily in Age and Cabin columns
- Clear correlations between certain features were identified

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
- NumPy for numerical operations

## How to Run
1. Ensure you have Python installed
2. Install required libraries:
   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. Download the Titanic dataset
4. Run the Jupyter notebook

## Future Improvements
- Implement statistical tests
- Add more feature engineering
- Develop predictive models
