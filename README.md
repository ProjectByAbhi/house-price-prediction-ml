# House Price Prediction using Machine Learning

This project compares multiple machine learning models to predict house prices using the **California Housing Dataset**.

## Project Overview

The goal of this project is to train and compare different regression models to determine which performs best for predicting house prices.

## Dataset

The dataset used is the **California Housing Dataset** provided by Scikit-learn.

Features include:

* Median Income
* House Age
* Average Rooms
* Average Bedrooms
* Population
* Households
* Latitude
* Longitude

Target Variable:

* **House Price**

## Models Used

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

## Evaluation Metrics

The models were evaluated using:

* RMSE (Root Mean Squared Error)
* R² Score

## Results

| Model             | RMSE     | R² Score |
| ----------------- | -------- | -------- |
| Linear Regression | 0.745581 | 0.575788 |
| Ridge Regression  | 0.745554 | 0.575819 |
| Decision Tree     | 0.724234 | 0.599732 |

Best Model: **Decision Tree Regressor**

## Project Structure

AI_ML_Task2

* AI_ML_Task2_Model_Comparison.ipynb
* report.pdf
* requirements.txt
* house_price_model.pkl

## How to Run

1. Install required libraries

pip install -r requirements.txt

2. Open the notebook

jupyter notebook

3. Run all cells.

## Author

Abhishek
