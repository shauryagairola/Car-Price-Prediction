# Car Price Prediction Using Machine Learning

## Project Overview

This project develops a machine learning model to predict the selling price of used cars based on vehicle characteristics. This is a used case project in Machine Learning ie. Car Price Prediction.  Machine learning model used - Linear Regression , LASSO Regression.

## Objectives

- Analyze used-car data
- Perform data preprocessing
- Encode categorical variables
- Perform exploratory data analysis
- Train regression models
- Compare Linear Regression and Lasso Regression
- Evaluate model performance using R²

## Dataset

The dataset contains 301 observations and 9 attributes:

- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

### Linear Regression

Training R²: 0.8799  
Test R²: 0.8366

### Lasso Regression

Training R²: 0.8428  
Test R²: 0.8709

## Project Workflow

Data Collection
→ Data Cleaning
→ EDA
→ Feature Encoding
→ Train/Test Split
→ Model Training
→ Model Evaluation
→ Price Prediction

## Results

Lasso Regression achieved the higher test R²
on the selected train-test split.

## Project Structure

Car-Price-Prediction/
│
├── Car Price Prediction.ipynb
├── car data.csv
├── README.md
└── images/

## Author

Shaurya Gairola

M.Sc. Data Science
PRN: 2403914200078

## Repository

https://github.com/shauryagairola/Car-Price-Prediction
