# compare-ML-models

This file takes a default dataset from sklearn, and analyze the performance of the following models:

Linear Regression,
Elastic Net,
Ridge Regression,
Decision Tree,
Random Forest,
KNeighborsRegressor,
GradientBoosting Regressor.

The metric for evaluation is MSE (mean squared error) on a 5-fold cross-validation set.

For each model, we evaluate the MSE under default hyper-parameters, and the best hyper-parameters found through GridSearchCV. 
