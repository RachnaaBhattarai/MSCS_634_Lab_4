# Lab 4: Regression Analysis with Regularization Techniques

## Purpose of the Lab
The primary objective of this lab was to apply and compare various regression techniques on the Diabetes dataset to understand how different models perform in predicting disease progression. The lab focused on implementing simple linear regression, multiple linear regression, polynomial regression, and regularized regression methods (Ridge and Lasso), with the goal of evaluating model accuracy, handling overfitting, and identifying relevant features.

## Key Insights from the Regression Analysis
Through this lab, we observed that using a single feature (BMI) in simple linear regression resulted in limited performance (R² = 0.23), while incorporating all features in multiple regression significantly improved the model (R² = 0.45). Polynomial regression added complexity without substantial gains. Regularization techniques, especially **Lasso Regression with α = 0.1**, provided the best results (R² = 0.47) by improving accuracy and automatically performing feature selection. Ridge regression also helped mitigate overfitting when properly tuned. These findings emphasize the value of regularization and feature selection in building effective predictive models.

## Challenges and Decisions Made
One key challenge was tuning the hyperparameters (alpha values) for Ridge and Lasso regression to balance bias and variance. Another consideration was choosing the appropriate polynomial degree that adds value without causing overfitting. Decisions were made to standardize the comparison by using consistent train-test splits and evaluation metrics (MAE, MSE, RMSE, R²). The lab reinforced the importance of experimenting with different models and parameters to find the most robust solution.
