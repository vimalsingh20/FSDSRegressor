# Diamond Price Prediction

This is an end-to-end Machine Learning project that predicts the price of a diamond based on different features such as carat, depth, table, cut, color and clarity.

## Project Overview

In this project, I have created a complete machine learning pipeline starting from data ingestion and data transformation to model training and prediction.

The project compares different regression models and selects the best model based on the R2 score.

The trained model and preprocessor are then used in a Flask web application to predict the diamond price based on user input.

## Features

- Data ingestion and train-test splitting
- Data preprocessing and transformation
- Handling numerical and categorical features
- Feature scaling using StandardScaler
- Ordinal encoding for categorical features
- Multiple regression models
- Model evaluation using R2 score
- Automatic selection of the best model
- Flask web application for prediction
- Custom logging and exception handling
- Docker support

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- Docker

## Machine Learning Models

The following models are trained and compared:

- Linear Regression
- Lasso Regression
- Ridge Regression
- ElasticNet Regression

The model with the best R2 score is selected and saved for prediction.

## Input Features

The application takes the following inputs:

- Carat
- Depth
- Table
- Cut
- Color
- Clarity

The target variable is `price`.

## Project Structure

```text
Diamond_Prediction/
│
├── artifacts/
├── notebooks/
├── src/
├── templates/
├── app.py
├── Dockerfile
├── requirements.txt
├── setup.py
└── README.md