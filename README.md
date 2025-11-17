# AI-ML-Internship-Tasks
Collection of AI/ML internship projects demonstrating data analysis, regression, classification, and predictive modeling. Includes tasks on stock price prediction, heart disease prediction, house price prediction, and data visualization using Python, scikit-learn, and related libraries.

AI/ML Internship Projects
Overview

This repository contains AI/ML projects completed during my internship, covering regression, classification, and data analysis tasks. Each project demonstrates practical skills in data preprocessing, modeling, evaluation, and visualization.

Task 1: Exploring and Visualizing a Simple Dataset (Iris Dataset)

Objective:
Understand and visualize dataset trends using descriptive statistics and plots.

Dataset:
Iris Dataset (CSV or built-in seaborn dataset)

Approach:

Loaded dataset using pandas

Performed data inspection using .head(), .info(), .describe()

Created scatter plots, histograms, and boxplots to analyze distributions and outliers

Key Skills:
Data loading, descriptive statistics, data visualization using matplotlib and seaborn

Key Findings:

Visualizations revealed clear separation between species

Boxplots identified potential outliers in petal and sepal dimensions

Task 2: Predict Future Stock Prices (Short-Term)

Objective:
Predict the next day’s stock closing price using historical data.

Dataset:
Stock market data retrieved from Yahoo Finance using yfinance

Approach:

Features used: Open, High, Low, Volume

Models applied: Linear Regression / Random Forest Regression

Visualized predicted vs actual closing prices

Key Skills:
Time series handling, regression modeling, data fetching via APIs, plotting predictions

Key Findings:

Models captured trends in stock prices with reasonable accuracy

Linear Regression provided a baseline; Random Forest improved prediction accuracy

Task 3: Heart Disease Prediction

Objective:
Predict risk of heart disease based on health metrics.

Dataset:
Heart Disease UCI Dataset (Kaggle)

Approach:

Data cleaning and missing value handling

Exploratory Data Analysis (EDA) for trends

Classification models applied: Logistic Regression, Decision Tree

Evaluated using Accuracy, ROC curve, Confusion Matrix

Analyzed important features affecting predictions

Key Skills:
Binary classification, medical data interpretation, model evaluation, feature importance

Key Findings:

Key features influencing heart disease risk: age, cholesterol, blood pressure

Logistic Regression provided interpretable results; Decision Tree captured non-linear relationships

Task 6: House Price Prediction

Objective:
Predict house prices using property features such as size, bedrooms, and location.

Dataset:
House Price Prediction Dataset (Kaggle)

Approach:

Data preprocessing: handled missing values, encoded categorical features, scaled numerical features

Models applied: Linear Regression, Gradient Boosting Regression

Evaluated using MAE (Mean Absolute Error) and RMSE

Visualized predicted prices vs actual prices

Key Skills:
Regression modeling, feature scaling and selection, evaluation metrics, real estate data analysis

Key Findings:

Gradient Boosting provided higher accuracy than Linear Regression

House size and location had the most significant impact on price
