# House Price Prediction using XGBoost Regression

## Overview

This project builds a Machine Learning regression model to predict house prices using the California Housing Dataset. The objective is to analyze housing-related features and accurately estimate property values using the XGBoost Regression algorithm.

The project demonstrates the complete Machine Learning workflow, including data loading, exploratory data analysis (EDA), feature-target separation, model training, evaluation, and visualization of predictions.

---

## Problem Statement

House prices are influenced by several factors such as income levels, housing age, room distribution, occupancy, and geographical location.

The goal of this project is to develop a predictive model that learns patterns from historical housing data and estimates house prices for unseen examples.

---

## Dataset

Dataset: California Housing Dataset

The dataset was obtained using Scikit-Learn's built-in housing dataset.

### Features

* MedInc – Median income
* HouseAge – Median house age
* AveRooms – Average rooms per household
* AveBedrms – Average bedrooms per household
* Population – Block population
* AveOccup – Average household occupancy
* Latitude
* Longitude

### Target Variable

* Price – Median house value

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

Loaded the California Housing Dataset using Scikit-Learn.

### 2. Data Preparation

* Converted the dataset into a Pandas DataFrame
* Added the target variable (Price)
* Checked for missing values
* Generated descriptive statistics

### 3. Exploratory Data Analysis (EDA)

* Analyzed feature relationships
* Computed correlation matrix
* Visualized correlations using a heatmap

### 4. Feature and Target Separation

Input Features (X):

* Housing attributes

Target Variable (Y):

* House Price

### 5. Train-Test Split

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

Random State:

* 2

### 6. Model Training

Algorithm Used:

### XGBoost Regressor

XGBoost (Extreme Gradient Boosting) is a powerful ensemble learning algorithm based on gradient-boosted decision trees. It is widely used for structured/tabular datasets due to its strong predictive performance and ability to model complex non-linear relationships.

---

## Model Evaluation

The model was evaluated on both training and testing datasets using:

### R² Score

Measures how well the model explains the variance in house prices.

### Mean Absolute Error (MAE)

Measures the average prediction error in house price estimation.

---

## Visualization

The project includes scatter plots comparing:

* Actual House Prices
* Predicted House Prices

These visualizations help assess how closely model predictions match real values.

---

## Key Learning Outcomes

Through this project, I gained hands-on experience in:

* Data preprocessing using Pandas
* Exploratory Data Analysis (EDA)
* Correlation analysis and heatmap visualization
* Feature-target separation
* Train-test splitting
* XGBoost Regression
* Model evaluation using R² Score and MAE
* Visualization of regression results
* Building end-to-end Machine Learning pipelines

---

## Future Improvements

Potential enhancements include:

* Hyperparameter tuning for XGBoost
* Cross-validation
* Feature engineering
* Comparison with Linear Regression, Random Forest, and Gradient Boosting models
* Model deployment using Flask or Streamlit

---

## Author

**N C Kartheek Reddy**

B.Tech Computer Science & Engineering
VIT-AP University

GitHub: github.com/chaitanyanevali
