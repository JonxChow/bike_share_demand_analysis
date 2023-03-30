# Welcome to Bike-Sharing Analysis Repository

## About 

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on bike sharing demand. For detailed walkthrough, please view the source code in order from:

  1. Libraries and Data Loading
  2. Data Cleaning
  3. Descriptive Analysis
  4. Model Fitting
  5. K-Nearest Neighbor

## Contributors

  * @lalooms - Model Fitting, KNN
  * @KzRihan - Libraries and Data Loading, Descriptive Analysis
  * @jacobrossman79 - Data Cleaning

## Problem Definition

  * Are we able to forecast use of a bikeshare system?
  * Which model would be the best to predict?

## Models Tested

  1. RandomForestRegressor
  2. AdaBoostRegressor
  3. BaggingRegressor
  4. SVR 
  5. KNeighborsRegressor

## Conclusion
  * Count is dependent on 'casual' and 'registered' variables
  * Count is highly skewed to the left and would need to be normalized before model fitting
  * 'Hour', 'Month' and 'Season' have a high correlation value with Count
  * KNN has the lowest error and highest R2 value out of the 5 models tested
  * Yes, it is possible to forecast use of a bikeshare system

## What did we learn from this project?
  * Handling skewed target variable using log function
  * New methods for error measurement (RMLSE, MAE)
  * K Nearest Neighbor from sklearn
  * Collaborating using Collab
  * Concepts on Phi Coefficient and Point Biserial Correlation Coefficient(PBCC)


## References
  * https://www.kaggle.com/competitions/bike-sharing-demand/overview
  * https://www.ibm.com/sg-en/topics/knn
  * https://towardsdatascience.com/transforming-skewed-data-73da4c2d0d16
  * https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
  * https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingRegressor.html
  * https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostRegressor.html
  * https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html
