# Kaggle 2024 Tabular Playground Series - Used Car Price Prediction

This repository contains my solution for the **2024 Kaggle Tabular Playground Series** competition. The goal was to predict the price of used cars based on various features, using **Root Mean Squared Error (RMSE)** as the evaluation metric.

**Ranking**: 313th out of 3068 participants top 10%.

##  Approach

1. **Data Preprocessing**: 
   - Cleaned the data, handled missing values, and encoded categorical features.

2. **Feature Engineering**: 
   - Created new features (e.g., car age) and applied transformations to improve model performance.

3. **Modeling**: 
   - Used models like **LightGBM** and **XGBoost**.
   - Applied **Optuna** for hyperparameter optimization.

4. **Evaluation**: 
   - Cross-validated the models using RMSE.
