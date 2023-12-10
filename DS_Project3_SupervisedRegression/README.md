# House Price Prediction
Welcome to this repository! This repository focuses on a house price prediction project, in analyzing and modeling data related to predicting house prices. The project's goal is to deepen our understanding of factors influencing house prices and to build a predictive model facilitating early identification of price trends.

## Repository Contents:
### Dataset: 
- This dataset consists of 1460 rows and 81 columns.
- Independent variables contain house description data.
- The dependent variable refers to SalePrice.

### Features:
Read the column description in the link below:
https://github.com/MojjoMujju/DS_Project_Portfolio/blob/main/DS_Project3_SupervisedRegression/assets/data_description.docx

### Notebooks:
#### Data Preparation
- Train test split

#### EDA (Exploratory Data Analysis) & FE (Feature Engineering) : 
- Numerical and categorical column analysis (Handling Missing Values, Data Cleaning).
- Drop unused columns.
- Drop outlier.
- Transform Categorical features into Binary features.
- Log normalization.

#### Modelling
- Make models
- Models evaluation (RMSE - RSquare)
- Save the model to pickle

### Model Result:
![image](https://github.com/MojjoMujju/DS_Project_Portfolio/assets/84460310/41a42c52-1d15-41bc-a941-2d2774f77428)

### Report:
From the evaluation results of the models conducted, several key conclusions and insights can be drawn:
- Lasso Regression has the highest R-squared value (0.9103), indicating that this model explains the variation in the target very well.
- XGBoost and Ridge also exhibit good R-squared values, with scores of 0.9096 and 0.9087, respectively.
- LightGBM has a slightly lower R-squared value compared to the other models (0.8942), indicating slightly lower performance in explaining the target's variation.
- Lasso Regression has the lowest RMSE (0.1184), suggesting that this model has the lowest level of prediction error among the models.
- XGBoost and Ridge have nearly equally low RMSE values, around 0.1188 and 0.1195, respectively.
- LightGBM has a slightly higher RMSE (0.1286), indicating that this model has a higher level of prediction error compared to the other models.

Model Selection:

Based on the above results, Lasso Regression is a good choice as it has a high R-squared value and low prediction error.
