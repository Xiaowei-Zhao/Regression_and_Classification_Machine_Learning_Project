# Regression_and_Classification_Machine_Learning_Project

Task 1 Regression on Ames Housing Dataset 

1.1 Visualize the univariate distribution of each continuous, and the distribution of the target. 

1.2 Visualize the dependency of the target on each continuous feature (2d scatter plot).

1.3 Split data in training and test set. For each categorical variable, cross-validate a Linear Regression model using just this variable
(one-hot-encoded). Visualize the relationship of the categorical variables that provide the best
R^2 value with the target.

1.4 Use ColumnTransformer and pipeline to encode categorical variables. Evaluate Linear
Regression (OLS), Ridge, Lasso and ElasticNet using cross-validation with the default
parameters. 

1.5 Tune the parameters of the models using GridSearchCV. Visualize the dependence of the validation score on the parameters for Ridge, Lasso and ElasticNet.

1.6 Visualize the coefficients of the resulting models. 

Task 2 Classification on the Telco-churn dataset

2.1 Visualize the univariate distribution of each continuous feature, and the distribution of the
target.

2.2 Split data into training and test set. Build a pipeline for dealing with categorical variables.
Evaluate Logistic Regression, linear support vector machines and nearest centroids using
cross-validation.

2.3 Tune the parameters using GridSearchCV. Visualize the performance as function of the parameters for all three models.

2.4 Change the cross-validation strategy from 'stratified k-fold' to 'kfold' with shuffling. 

2.5 Visualize the coefficients for LogisticRegression and Linear Support Vector Machines using
hyper-parameters that performed well in the grid-search.
