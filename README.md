# Diamond Price Prediction using Machine Learning

## Description

This project aims to predict the price of diamonds based on various features such as carat, cut, color, clarity, and more. The goal is to build a machine learning model that can accurately predict diamond prices by learning patterns from a historical dataset.

## Dataset

The dataset used in this project is the publicly available **Diamond Dataset** from Kaggle. It contains various attributes of diamonds, including:

- **Carat**
- **Cut**
- **Color**
- **Clarity**
- **Depth**
- **Table**
- **Price**

The dataset is used to train and test machine learning models that can predict the price of diamonds based on these features.

## Models

Several machine learning models were trained and compared:

1. **Random Forest Regressor:** An ensemble method that combines multiple decision trees to improve prediction accuracy.
2. **XGBoost (without hyperparameters):** A gradient boosting algorithm used for regression, trained without hyperparameter tuning.
3. **XGBoost (with hyperparameters):** The XGBoost model optimized with hyperparameter tuning to improve performance.
4. **Decision Tree Regressor:** A simple regression model based on decision tree learning.
5. **Linear Regression:** A linear model that predicts diamond prices based on a linear relationship with the features.

All models were evaluated using cross-validation and performance metrics such as **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**.

## Results

The models achieved the following results on the validation set:

* **Random Forest Regressor:** [6.47% RMSE]
* **XGBoost (without hyperparameters):** [6.53% RMSE]
* **XGBoost (with hyperparameters):** [6.35% RMSE]
* **Decision Tree Regressor:** [8.50% RMSE]
* **Linear Regression:** [19.35% RMSE]

The **XGBoost (with hyperparameters)** model performed the best, outperforming the other models in terms of prediction accuracy.

## Instructions

### To run the project:
Open the ipynb file in this repository, and there click the **Open in colab** button

## Conclusion

This project demonstrates how machine learning techniques can be used to predict the price of diamonds based on various attributes. The results show that **XGBoost with hyperparameters** provides the most accurate predictions, offering valuable insights into the factors that influence diamond pricing.
