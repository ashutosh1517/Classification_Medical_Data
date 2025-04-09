# Classification_Medical_Data
Title - Cancer prediction based on input medical features using Ensemble ML algorithms

Dataset used - https://www.kaggle.com/datasets/erdemtaha/cancer-data

Overview -
This work is aimed to analyze a dataset of cancer patients and build a machine learning model to predict whether there is a cancer or not, with respect to some input medical features.

Workflow -
1. Data loading 
2. Basic data exploration and analysis - 
a) Exploring number of samples and features, name of the features, Dropping irrelevant features, 
b) Exploring the Target variable - “diagnosis”, 
c) Converting target class labels to numbers: 0 and 1.
d) Numerical analysis - overview of the entire dataset
e) Finding correlation of independent variables with target variable
f) Dropping features with very low correlation with target variable
g) Addressing Multicollinearity in the data
h) Dropping highly correlated independent features
i) Outlier detection and removal
j) Balancing class imbalance of the target variable
3. Feature scaling and preparing the data for modelling
4. Train and Test with 3 models - Logistic Reg., Random Forest, XGB
5. Evaluation of the model performances using accuracy metrics
6. Retraining the models with more data
7. Evaluation of the model performances using accuracy metrics
8. Feature selection is applied (SelectKbest, k = 10)
9. Retraining 3 models with selected input features
10. Evaluation of the models 
