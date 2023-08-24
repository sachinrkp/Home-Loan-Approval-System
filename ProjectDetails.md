# Projects
Home Credit Default Risk (Loan approval system)

Dataset link: https://www.kaggle.com/competitions/home-credit-default-risk/data

Jupyter Notebooks:

a) DataPreparation_1.ipynb -
1. Basic EDA and imputation of numerical and categorical predictors were performed.
2. Dropped several highly correlated features to reduce predictors.
3. Encoding of categorical predictors.
    
b) DataPreparation_2.ipynb -
1. Data Transformation (BoxCox, log, signed).
2. Data Normalisation (Min-Max)
    
c) FeatureSelection_3.ipynb -
1. Split train and validation data.
2. Apply XGBoost model with hyperparamter tuning.
3. Apply RandomForest model with hyperparamter tuning.
