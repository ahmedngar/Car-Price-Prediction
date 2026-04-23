# 🚗 Car Price Prediction Project

This repository contains a comprehensive Machine Learning project focused on predicting car prices. The project covers the entire pipeline from **Data Cleaning** and **Exploratory Data Analysis (EDA)** to model implementation using **Linear Regression**.

## 📊 Project Highlights
* **Dataset:** Analyzed car specifications (Make, Model, Year, Engine HP, etc.) to predict MSRP.
* **Mathematical Approach:** Implemented the **Normal Equation** for parameter estimation.
* **Evaluation Metric:** Used **RMSE (Root Mean Squared Error)** to evaluate the distance between predicted and actual prices.
* **Data Transformation:** Applied **Log Transformation** to the price target to handle skewed distributions.

## 🛠️ Tech Stack & Methodology
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`.
* **Feature Engineering:** * Handling categorical variables (Make, Model).
    * Derived new features (e.g., `age` of the car from the year).
    * Filled missing values using mean/zero imputation.
* **Model:** Linear Regression with **Regularization** to ensure the model generalizes well to new data.
