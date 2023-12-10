# Heart Disease Prediction

Welcome to this repository! This repository contains a heart disease prediction project, which is the result of collaborative efforts in analyzing and modeling heart health-related data. The project aims to enhance our understanding of factors that can influence the risk of heart disease and to develop a predictive model that can assist in early identification.

![image](https://github.com/MojjoMujju/DS_Project_Portfolio/assets/84460310/e99f113a-342e-411d-8a24-043cd8f37a8e)

## Repository Contents:
### Dataset: 
- This dataset consists of 5110 rows and 11 columns.
- Independent variables contain patient-related data.
- The dependent variable refers to heart disease.

### Features:
1. id: unique identifier
2. gender: "Male", "Female," or "Other"
3. age: age of the patient
4. hypertension: 0=if the patient doesn't have hypertension, 1=if the patient has hypertension
5. ever_married: "No" or "Yes"
6. work_type: "children," "Govt_job," "Never_worked," "Private," or "Self-employed"
7. Residence_type: "Rural" or "Urban"
8. avg_glucose_level: average glucose level in blood
9. BMI: body mass index
10. smoking_status: "formerly smoked," "never smoked," "smokes," or "Unknown"*
11. heart_disease: 0= if the patient doesn't have any heart diseases, 1= if the patient has a heart disease

### Notebooks:
#### EDA (Exploratory Data Analysis) : 
- Check dataset information.
- Check dependent column proportion.
- Check missing values.
- Numerical and categorical column analysis.
- Check the Correlation in some columns to get Insight.
- EDA Insight

#### FE (Feature Engineering):
- Dataset cleaning (drop columns and remove unused values)
- Data encoding
- Handling missing values
- Features scaling

#### Model Preparation
- Train test split

#### Modelling
- Make models
- Models evaluation (Confusional matrix - Test various neighbors - classification report)
- Save the model to pickle

### Model Result:
![image](https://github.com/MojjoMujju/DS_Project_Portfolio/assets/84460310/d13bccf3-a627-4454-b3e7-082f570f4bbc)

### Report:
From the results of machine learning modeling, it can be concluded that the best model for predicting heart disease is using the KNN algorithm with a number of neighbors equal to 5.
