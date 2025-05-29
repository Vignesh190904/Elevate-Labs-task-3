# Titanic Fare Prediction using Linear Regression

## Objective
Implement and analyze Simple and Multiple Linear Regression using the Titanic dataset to predict passenger fare.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Dataset
Titanic-Dataset.csv from Kaggle. We used only numerical features: `Age`, `Pclass`, `SibSp`, `Parch`, and `Fare`.

## Steps

### 1. Data Preprocessing
- Selected numerical columns relevant for regression.
- Dropped rows with missing values.

### 2. Simple Linear Regression
- Predicted `Fare` using only `Age`.
- Evaluated using MAE, MSE, and R² score.
- Visualized regression line.

### 3. Multiple Linear Regression
- Used `Age`, `Pclass`, `SibSp`, and `Parch` as features.
- Evaluated model performance using the same metrics.

## Results
- Regression models were fit and interpreted.
- Plots and scores help understand how well linear regression models predict fare.

## Author
This project was completed as part of a Machine Learning exercise on Linear Regression.

