# TitanicSurvivalPredictions

This repository is for one of my first attempts at the Titanic Kaggle competition (https://www.kaggle.com/c/titanic/overview)

I recieved 79.4% accuracy on the test set using the following method:

1) Cleaned the data, numerized columns, feature engineered and filled in blank values for important columns (except age).
2) Used grid search and cross validation to identify the best model and parameters to predict age.
3) Filled in age and turned it into a categorical variable.
4) Used grid search and cross validation to identify the best model and parameters to predict survival.
5) Use the best model to produce the predictions on the test data.
