# House Prices Regression

## 📌 Project Description
The project aims to predict house prices using various machine learning techniques. It uses a dataset from the Kaggle competition, containing information on different house features. The goal is to build a regression model that accurately predicts house prices based on those features.

## 📊 Data Description

The dataset includes the following features:
- **OverallQual** — overall material and finish quality,
- **GrLivArea** — above-ground living area in square feet,
- **YearBuilt** — year the house was built,
- **1stFlrSF** — first-floor square footage,
- **TotalBsmtSF** — total basement square footage,
- **and other features** like neighborhood, lot area, number of rooms, and more.

The target variable (**SalePrice**) represents the sale price of the house.

## 🔍 Data Preprocessing
1. **Data Analysis** — exploring and analyzing the dataset for missing values, distributions, and correlations.
2. **Feature Generation** — creating new features from existing ones based on domain knowledge.
3. **Feature Removal** — eliminating features with little impact on the target variable.
4. **Visualization** — visualizing features and relationships using various plots and graphs.
5. **Log Transformation** — applying a logarithmic transformation to the target variable (**SalePrice**) to reduce skewness and better meet model assumptions.

## 🔬 Linear Regression
- The project involved implementing both **Numerical** and **Analytical** methods for **Linear Regression** as separate classes.
- The results were compared with the standard **Linear Regression** model from the **sklearn** library.

## 🏆 Results
- The best model achieved an **MSE (Mean Squared Error)** of **0.0105**.
