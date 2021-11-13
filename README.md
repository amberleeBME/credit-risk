# Supervised Machine Learning:</br>Predicting Credit Risk
## Objective:
Create machine learning models to classify the risk level of loans, specifically, comparing the Logistic Regression (LR) model and Random Forest Classifier (RFC).
## Analysis:
1. **Preprocessing**: `2019loans.csv` and `2020Q1loans.csv` were retrieved using Pandas as training and testing data, respectively. Categorical data was converted to numeric columns using `pd.get_dummies()`
2. **Fit models**: The data was first fitted to a LR model and then the same was done for RFC</br>
    > `LR Training Data Score: 0.648440065681445` </br>
    > `LR Testing Data Score: 0.5253083794130158` </br>
    > `RFC Training Score: 1.0` </br>
    > `RFC Testing Score: 0.63143343258188` </br>

3. **Revisit the Preprocessing (Scale the data)**: The data was scaled using `StandardScalar`.
4. **Re-fit models**:
    > `LR Training Data Score: 0.713136288998358` </br>
    > `LR Testing Data Score: 0.7207571246278179` </br>
    > `RFC Training Score: 1.0` </br>
    > `RFC Testing Score: 0.6337728626116547` </br>

## Reflection:
The logistical regression model performed the best, especially after scaling the data.  
