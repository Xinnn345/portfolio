
---
title: Analyzing Crime Distribution and Prevention Strategies in Malaysia
permalink: /projects/food-delivery-risk/
---

[Home](../README.md) | [All Projects](../projects.md)

# Analyzing Crime Distribution and Prevention Strategies in Malaysia
<p align="center">
  <img src="../crime.png" width="950">
</p>

## Project Overview

This project applies data analytics and machine learning to analyze crime distribution and trends across Malaysia, while investigating the relationships between crime rates and socioeconomic indicators.

Using historical crime statistics and socioeconomic data from OpenDOSM, the study develops predictive models to identify crime patterns and generate insights that can support evidence-based crime prevention strategies.

## Objectives

1. To analyze crime distribution and trends across Malaysian states and years.
2. To examine relationships between crime rates and socioeconomic indicators, including household income, unemployment and education completion rates.
3. To develop machine learning models to predict crime distribution and provide data-driven insights for crime prevention and policy planning.

## Tools and Technologies

- **Programming:** Python
- **Database:** PostgreSQL
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost, CatBoost, LightGBM
- **Model Deployment:** Streamlit, Power BI
- **Development Environment:** Google Colab

## Methodology

### 1. Dataset Collection and Integration
Collected four datasets from OpenDOSM, covering crime statistics, household income, annual labour force statistics and school completion rates in Malaysia. The datasets cover different time periods, with the main crime dataset spanning 2016–2023.

Used PostgreSQL to integrate multiple datasets based on relevant geographical and time-related attributes, creating a consolidated dataset for further analysis.

### 2. Data Cleaning and Preprocessing
Performed data quality checks to identify missing values and duplicate records. Handled missing numerical values using district-level averages, time-series interpolation and overall variable averages, while removing incomplete categorical records.

Removed redundant aggregate records and irrelevant variables, applied label encoding to categorical features, and investigated outliers to determine whether they represented meaningful variations in the data.

### 3. Exploratory Data Analysis (EDA) and Feature Selection
Conducted exploratory data analysis using descriptive statistics, correlation heatmaps and distribution plots to examine crime patterns and relationships with socioeconomic indicators.

Applied ANOVA and Pearson correlation-based feature selection to identify statistically significant variables. Selected relevant features, including household income, unemployment population and school completion rates, for machine learning development.

### 4. Machine Learning Model Development
Developed and compared four supervised regression models: XGBoost, CatBoost, LightGBM and HistGradient Boosting.

Split the dataset into 80% training and 20% testing data. Applied RandomizedSearchCV for hyperparameter tuning and evaluated model performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE) and R-squared (R²).

### 5. Model Evaluation and Selection
Compared the performance of all four regression models based on prediction errors, explanatory power and training efficiency.

Selected LightGBM as the final model due to its lowest prediction errors and highest R-squared value, making it the most suitable model for predicting crime distribution in this study.

### 6. Model Deployment and Dashboard Development
Serialized the trained LightGBM model and integrated it into an interactive Streamlit web application.

Developed an application with three main functional sections:
- **Dashboard:** Explore historical crime distribution from 2016–2023, filter by state, crime category and year, and identify the top five recorded crime types.
- **Prediction:** Generate crime predictions for selected states, crime categories and future years using the trained LightGBM model.
- **Alerts & Feedback:** Display crime prevention reminders and allow users to submit feedback on application functionality and prediction results.

The application provides an accessible platform for exploring crime trends and supporting data-driven decision-making.

[Live Application](https://crime-app-analysis.streamlit.app/)

## Key Findings

### 1. Crime Distribution and Trends
Identified variations in crime distribution across Malaysian states and years. Property crimes, particularly vehicle theft and motorcycle theft, were among the most common crime types, with notable concentrations in urban areas such as Kuala Lumpur and Selangor.

### 2. Socioeconomic Relationships
Identified moderate positive correlations between household income and crime, while unemployment showed a weaker positive relationship. The analysis also highlighted relationships between education completion rates and crime distribution.

### 3. Machine Learning Performance
LightGBM achieved the best overall regression performance among the four evaluated models:
- **MAE:** 31.2143
- **MSE:** 5,456.6366
- **RMSE:** 73.8690
- **R²:** 0.5208

The R² result indicates that approximately 52.08% of the variation in crime outcomes was explained by the model.

### 4. Application Development
Successfully deployed the selected LightGBM model through Streamlit, integrating historical crime analysis, predictive modelling and an interactive feedback system into one application.

The system allows users to explore crime patterns across 14 Malaysian states and generate predictions for selected future years.


## Project Links

- Dataset: [Food Delivery Apps Reviews on Kaggle](https://www.kaggle.com/datasets/skamlo/food-delivery-apps-reviews)
- GitHub Source Code: [GitHub Repository](https://github.com/XINnn2/FOOD)
- Live Streamlit App: [Food Delivery Complaints Apps](https://complaint-system.streamlit.app/)
- Finding Report: [Report](https://canva.link/78hec0napcbogm4)

</br>
</br>

[Back to Previous Page](../projects.md)
