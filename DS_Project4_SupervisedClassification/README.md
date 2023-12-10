# Churn Prediction
It is the dataset of a U.S. bank customer for getting information on whether a customer will leave the bank or not. Various Bank detail is given like CustomerID, surname, Credit score, and many more. This dataset originated from a U.S. bank.

## Repository Contents:
### Dataset: 
- This dataset consists of 10000 rows and 14 columns.
- Independent variables contain customer data.
- The dependent variable refers to Exited.

### Features:
 1. RowNumber: 
 2. CustomerId:
 3. Surname: Surname
 4. CreditScore: Credit score
 5. Geography: Country (Germany / France / Spain)
 6. Gender: Gender (Female / Male)
 7. Age: Age
 8. Tenure: How many years of customer
 9. Balance: Balance
 10. NumOfProducts: Bank product used
 11. HasCrCard: Credit card status (0 = No, 1 = Yes)
 12. IsActiveMember: Active membership status (0 = No, 1 = Yes)
 13. EstimatedSalary: Estimated salary
 14. Exited: Abandoned or not? (0 = No, 1 = Yes)

### Notebooks:
#### Data Preparation
- Train test split

#### EDA (Exploratory Data Analysis): 
- Outlier Observe.
- Numerical and Categorical Columns Analysis.
- Log normalization.

#### FE (Feature Engineering):
- Outlier Suppression.
- Numerical to Categorical (Make Numerical Column into Categorical)
- Data Cleaning.
- Data Encoding

#### Modelling
- Make models
- Models evaluation (Confusion Matrix - Classification Report)
- Save the model to pickle

### Model Result:
![image](https://github.com/MojjoMujju/DS_Project_Portfolio/assets/84460310/781f9032-b54b-474a-9923-ce89312edf92)

### Report:
#### Best Accuracy Model:
The model with the highest accuracy is XGBoost and LightGBM with an accuracy rate of 88%.

#### Model with the Highest Precision in Class 0:
The model with the highest precision in class 0 (non-churn) is LightGBM with a precision rate of 90%. This indicates that the model is quite good at avoiding errors in predicting actual non-churn instances.

#### Model with the Highest Recall in Class 0:
The model with the highest recall in class 0 (non-churn) is Random Forest with a recall rate of 97%. This implies that the model is quite effective at avoiding errors in predicting actual non-churn instances.

#### Model with the Highest F1-Score in Class 0:
The models with the highest F1-Score in class 0 (non-churn) are LightGBM and XGBoost with an F1-score of 93%. This indicates that the models are quite effective at avoiding errors in predicting actual non-churn instances.

#### Model with the Highest Precision in Class 1:
The model with the highest precision in class 1 (churn) is XGBoost with a precision rate of 75%. This means that the model is quite effective at avoiding errors in predicting actual churn instances.

#### Model with the Highest Recall in Class 1:
The model with the highest recall in class 1 (churn) is LightGBM with a recall rate of 52%. This indicates that the model is less effective at avoiding errors in predicting actual churn instances.

#### Model with the Highest F1-Score in Class 1:
The models with the highest F1-Score in class 1 (churn) are LightGBM and XGBoost with an F1-score of 60%. This indicates that the models are quite effective at avoiding errors in predicting actual churn instances.
