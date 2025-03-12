# OIBSIP_unemployment_anaysis_using_python
# OIBSIP_2

## Overview
This is a Python-based data science project that aims to analyze the unemployment rate during Covid-19 using two different CSV files containing relevant data. The project involves data preprocessing, feature engineering, and machine learning to predict and understand the factors contributing to the unemployment rate increase during the pandemic.

## Data Sources
- First CSV File: "Unemployment in India"
  - Columns: Region, Date, Frequency, Estimated Unemployment Rate (%), Estimated Employed, Estimated Labour Participation Rate (%), Area
  
- Second CSV File: "Unemployment_Rate_upto_11_2020"
  - Columns: Region, Date, Frequency, Estimated Unemployment Rate (%), Estimated Employed, Estimated Labour Participation Rate (%), Region, longitude, latitude

Both CSV file upladed here

## Dependencies
- pandas
- numpy
- matplotlib
- scikit-learn

## Steps
1. Load and merge the two CSV files using 'Region' and 'Date' as common keys.
2. Preprocess the data by dropping unnecessary columns and handling missing values.
3. Perform feature engineering by extracting the month and year from the 'Date' column.
4. Prepare the data for machine learning by defining features and the target variable.
5. Split the data into training and testing sets for model evaluation.
6. Train different machine learning models (Linear Regression, Random Forest, SVR) and evaluate their performance using cross-validation and Mean Squared Error (MSE).
7. Perform feature selection using Recursive Feature Elimination (RFE) with Linear Regression.
8. Train the Linear Regression model with the selected features and evaluate its performance using MSE and R-squared.

## Expected Output
- The project outputs the Mean Squared Error and R-squared values for each model, as well as the RFE-based Linear Regression model's evaluation metrics.

## How to Use
1. Ensure the required dependencies are installed.
2. Update the file paths for the two CSV files: "Unemployment in India" and "Unemployment_Rate_upto_11_2020".
3. Run the code to execute the ML project.
4. Analyze the output to understand the performance of different ML models and the importance of features in predicting the unemployment rate.

## Improvements
This project can be further enhanced by trying different algorithms, performing hyperparameter tuning, and exploring additional feature engineering techniques. Additionally, acquiring more relevant data and domain knowledge can lead to a better understanding of the factors influencing the unemployment rate during Covid-19.

## Disclaimer
The analysis in this project is based on the data available up to the date of the CSV files. For real-world decision-making, it is essential to consider more up-to-date and comprehensive data sources.

