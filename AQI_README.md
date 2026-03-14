# 🌫️ Air Quality Index (AQI) Prediction -- Machine Learning Project

------------------------------------------------------------------------

## 👤 Author

**Pallavi Arshanapelli**\
B.Tech CSE (AI & DS) -- Marwadi University\
LinkedIn: https://www.linkedin.com/in/arshanapelli-pallavi-0b577349/

------------------------------------------------------------------------

## 📌 Project Overview

This project focuses on predicting the **Air Quality Index (AQI)** using
machine learning.\
The dataset contains pollutant concentrations, weather conditions, and
time‑based features.

The goal is to understand how environmental factors affect air quality
and build a model that can accurately predict AQI levels.

------------------------------------------------------------------------

## 🎯 Project Objectives

-   Clean and prepare the air quality dataset\
-   Perform Exploratory Data Analysis (EDA)\
-   Understand relationships between pollutants and AQI\
-   Create useful features from time and environmental data\
-   Train a Machine Learning model for AQI prediction\
-   Evaluate model performance using regression metrics

------------------------------------------------------------------------

## 🧹 Data Cleaning Process

-   Removed unnecessary spaces from column names\
-   Converted date column into datetime format\
-   Extracted time features such as month, hour, and season\
-   Checked for missing values and duplicates\
-   Handled outliers using the IQR method\
-   Verified and corrected data types

------------------------------------------------------------------------

## 📊 Exploratory Data Analysis (EDA)

Several visualizations were created to understand the data:

-   Pollutant concentration vs AQI analysis\
-   Weather conditions vs AQI relationship\
-   Monthly AQI trend analysis\
-   Hourly AQI variation analysis\
-   Correlation heatmap between features

These analyses help identify patterns in pollution levels.

------------------------------------------------------------------------

## 🤖 Machine Learning Model

A **Linear Regression model** was used to predict AQI values.

### Steps Followed

1.  Train‑Test Split\
2.  Feature Scaling using StandardScaler\
3.  Model Training using Linear Regression\
4.  Prediction on test data\
5.  Model Evaluation

------------------------------------------------------------------------

## 📈 Model Evaluation

The model was evaluated using the following metrics:

-   **MAE (Mean Absolute Error)**
-   **MSE (Mean Squared Error)**
-   **RMSE (Root Mean Squared Error)**
-   **R² Score**

### Model Performance

-   MAE ≈ **16**
-   RMSE ≈ **22**
-   R² Score ≈ **0.98**

The model explains approximately **98% of the variation in AQI**,
showing strong prediction performance.

------------------------------------------------------------------------

## 🔑 Key Insights

-   **PM10 and PM2.5 are the strongest contributors to AQI**
-   Seasonal changes affect pollution levels
-   Winter months often show higher pollution
-   Weather conditions influence pollutant dispersion
-   Predicted AQI values closely match actual AQI values

------------------------------------------------------------------------

## 📊 Visualizations Included

-   Actual vs Predicted AQI Plot\
-   Residual Distribution Plot\
-   Feature Importance Plot\
-   Pollutant vs AQI Analysis\
-   Weather vs AQI Analysis\
-   Correlation Heatmap

These visualizations help interpret the model and understand
environmental patterns.

------------------------------------------------------------------------

## 🛠 Tools & Technologies

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn\
-   Scikit‑Learn
