# House Price Prediction using Linear Regression

## Project Overview

This project implements a Multiple Linear Regression model to predict house prices based on three important features:

* Square footage / living area
* Number of bedrooms
* Number of bathrooms

The model is trained using the House Prices dataset from Kaggle.

## Dataset

Dataset: House Prices - Advanced Regression Techniques

The dataset can be downloaded from Kaggle:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## Features

The following features are used for prediction:

* `GrLivArea` - Above-ground living area in square feet
* `BedroomAbvGr` - Number of bedrooms
* `FullBath` - Number of full bathrooms

Target variable:

* `SalePrice` - House sale price

## Machine Learning Model

Multiple Linear Regression is used for predicting house prices.

The dataset is divided into:

* 80% Training data
* 20% Testing data

## Model Evaluation

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Project Structure

```text
house-price-prediction-linear-regression/
│
├── House_Price_Prediction_Linear_Regression.ipynb
└── README.md
```

## Conclusion

The Multiple Linear Regression model predicts house prices using square footage, bedrooms, and bathrooms. The model's performance is evaluated using standard regression metrics such as RMSE and R² score.
