# India Crime Data Visualization and Prediction

### Overview

This project aims to analyze and visualize crime data in India, providing insights into crime patterns and leveraging machine learning for predictive analysis. The project includes data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling.

### Dataset

The dataset is contained in the Crime in India.zip archive, comprising various CSV files detailing different aspects of crime in India:

- Property stolen and recovered
- Crime against women
- Human rights violations by police
- Complaints against police
- Murder victim statistics

Each file provides data on specific crime categories, enabling a comprehensive analysis.

### Features

##### 1. Exploratory Data Analysis (EDA)
- Annual Property Stolen vs. Recovered: Bar charts illustrating trends over years.
- Recovery Rates by Region: Bar charts highlighting recovery efficiency in different areas.
- Trends in Stolen Property Cases by Area: Line plots showing yearly trends in cases.

##### 2. Predictive Analysis
- Recovery Rate Prediction: Using features like year, value of stolen property, and region to predict recovery rates with a Random Forest Regressor.
- Hyperparameter Tuning: Grid Search for optimizing model parameters.
- Visualization of Predicted vs. Actual Recovery Rates: Scatter plots to evaluate model performance.

##### 3. Visualizations
- Bar Charts: Recovery rates, regional comparisons, annual trends.
- Scatter Plots: True vs. predicted recovery rates.
- Annotated Visuals: Enhanced bar charts with annotations for better insights.

### Key Results

##### Visualization Insights
- Recovery Trends: Clear regional disparities in recovery rates.
- Annual Trends: Consistent patterns in property theft and recovery over the years.

##### Model Performance
- Mean Squared Error (MSE): Evaluated for both default and optimized models.
- Optimized MSE: Demonstrates significant improvement after hyperparameter tuning.

### Source

https://www.kaggle.com/datasets/rajanand/crime-in-india
