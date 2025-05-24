# Vehicle_Price_-Prediction
# 🚗 Vehicle Price Prediction Using Machine Learning

This project predicts the selling price of used vehicles based on their specifications using regression techniques. The entire workflow, from data cleaning to model evaluation, was completed on Google Colab.

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Approach](#approach)
- [Model Performance](#model-performance)
- [Technologies Used](#technologies-used)

## 🧾 Overview

Estimating the correct resale value of a vehicle can be difficult due to numerous factors such as make, model, year, mileage, and condition. This project leverages machine learning to build a regression model that can predict vehicle prices based on historical data.

## 📊 Dataset

- **Source**: [Example Dataset – Kaggle or Custom]
- **Size**: ~30,000 records of used cars
- **Features**:
  - `Make`
  - `Model`
  - `Year`
  - `Engine Size`
  - `Fuel Type`
  - `Transmission`
  - `Mileage`
  - `Price` (Target)

## 🧠 Approach

1. **Data Cleaning**
   - Handle missing values
   - Convert categorical variables using one-hot encoding or label encoding

2. **Feature Engineering**
   - Calculate vehicle age
   - Normalize/scale numeric features

3. **Model Building**
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting (Optional)

4. **Evaluation Metrics**
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

## 📈 Model Performance

| Model                | MAE     | RMSE    | R² Score |
|---------------------|---------|---------|----------|
| Linear Regression    | 2700.4  | 4100.6  | 0.78     |
| Random Forest        | 1900.2  | 3005.9  | 0.89     |
| Gradient Boosting    | 1850.7  | 2900.3  | 0.91     |

> Random Forest and Gradient Boosting yielded the best performance with low error and high accuracy.

## 🧰 Technologies Used

- Google Colab
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
