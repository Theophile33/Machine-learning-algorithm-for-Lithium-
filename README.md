Overview

The project contains a comprehensive machine learning pipeline for predicting Lithium (Li) concentrations in  East African carbonatite rocks.
 The code implements and compares multiple regression algorithms to identify the best-performing model for Lithium prediction based on geochemical features.


Requirements

*Jupyter Notebook 
* Python 3.7
* pandas 1.3.0
* numpy 1.21.0
* matplotlib 3.4.0
* seaborn 0.11.1
* scipy 1.7.0
* scikit-learn 0.24.0

Input Data Format:

The script expects a CSV file( with 53 features with Target Column :Lithium  and 648 rows ) 

Data source: available on demand

Model Evaluation

The pipeline compares the following algorithms:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Elastic Net
* Support Vector Regressor (SVR)
* k-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Gradient Boosting

Performance Metrics

* R² Score: Coefficient of determination
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)


Results Visualization

The script generates a 2x3 grid of scatter plots comparing actual vs predicted Lithium concentrations for 6 selected algorithms:
* Linear Regression
* Ridge Regression
* Lasso Regression
* Elastic Net
* Random Forest
* Gradient Boosting

Code repository: 

https://github.com/Theophile33/Machine-learning-algorithm-for-Lithium-/blob/main/Machine%20Learning%20for%20Lithium%20Prediction

