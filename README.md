🏡 Advanced House Price Prediction Project

This repository contains my solution for the Advanced House Price Prediction competition on Kaggle. The competition aims to predict the final sale price of homes in Ames, Iowa, based on various features about the properties. The goal of this project is to apply machine learning models and data analysis techniques to build an accurate price prediction model.


🚀 Project Overview

The dataset contains 79 explanatory variables that describe various aspects of residential homes, including property features, location, and market conditions. Our task is to predict the sale price (SalePrice) for each house based on these variables.


Competition Link:

Kaggle: Advanced House Price Prediction


🔍 Exploratory Data Analysis (EDA)


In the notebooks/EDA.ipynb, we explore the dataset to understand the distributions, relationships, and potential issues (e.g., missing data, outliers). Key findings from the EDA:


Missing Values: Several features have missing data, which need to be handled.
Feature Correlation: Some features, such as GrLivArea, OverallQual, and TotalBsmtSF, show a strong correlation with SalePrice.
Outliers: A few extreme outliers in the dataset can significantly affect model performance.


🛠️ Feature Engineering


In the notebooks/Feature_Engineering.ipynb, various feature engineering techniques are applied:

Handling missing data: Replacing missing values with appropriate strategies (mean, median, mode, or using domain knowledge).
Encoding categorical variables: One-hot encoding and label encoding for categorical variables.
Creating new features: Combining existing features (e.g., total square footage).
Feature scaling: Applying normalization or standardization techniques to improve model performance.
