# 🌳 Predicting Height Based on Age using Decision Tree Regressor

This mini machine learning project uses a **Decision Tree Regressor** to predict a person's height based on their age. It’s a simple regression model that showcases how decision trees can be used for continuous output prediction.

## 📌 Project Overview

- **Model Used**: DecisionTreeRegressor (scikit-learn)
- **Features**: Age (independent variable)
- **Target**: Height (dependent variable)
- **R² Score**: 0.99
- **Root Mean Squared Error (RMSE)**: 1.13

## 📊 Dataset

A simple dataset with the following columns:
- `Age`: Age of a person
- `Height`: Height of a person

> Example:
>
> | Age | Height |
> |-----|--------|
> | 10   | 138  |
> | 11  | 138  |
> | 12   | 138  |
> | ... | ...    |

## 🔍 What I Did

- Imported and preprocessed the dataset
- Built a `DecisionTreeRegressor` model
- Evaluated model using **R² score** and **RMSE**
- Visualized the regression predictions and decision tree structure

## 📈 Visualization

### Decision Tree Regressor Plot
<img width="571" height="453" alt="DecisionTreeRegressor" src="https://github.com/user-attachments/assets/11039ae7-243e-4ed7-acaf-b26321755c26" />


### Prediction Plot
A plot comparing predicted height vs actual height using the trained model.
