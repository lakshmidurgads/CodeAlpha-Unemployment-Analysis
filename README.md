# CodeAlpha Unemployment Analysis

## Project Overview

This project analyzes unemployment trends in India using Python and machine learning techniques. The goal is to understand unemployment patterns and build a model to predict the unemployment rate based on selected factors.

## Dataset

The dataset contains unemployment-related information across different regions of India.

### Features

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Removed duplicate records
- Converted the Date column into a proper datetime format
- Created Year and Month features
- Converted relevant columns into numeric format

After preprocessing, the dataset contained **740 records and 7 columns**.

## Machine Learning Model

A **Random Forest Regressor** was used to predict the unemployment rate.

### Input Features

- Estimated Employed
- Estimated Labour Participation Rate (%)
- Year
- Month

### Target

- Estimated Unemployment Rate (%)

The dataset was divided into training and testing sets using an **80-20 split**.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Actual-versus-predicted analysis and feature importance visualization were also performed.

## Visualizations

The project includes visualizations showing:

- Unemployment trends
- Regional unemployment patterns
- Unemployment changes over time
- COVID-19 period comparison
- Actual vs predicted unemployment rates
- Feature importance

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Conclusion

This project demonstrates how data preprocessing, exploratory data analysis, visualization, and machine learning can be used to analyze unemployment trends and predict unemployment rates. The analysis provides useful insights into regional and time-based unemployment patterns in India.
