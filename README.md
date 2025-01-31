# Spam Classification with Logistic Regression

### Overview
This project applies a Logistic Regression model with ElasticNet regularization to classify spam emails using the UCI Spambase dataset. The implementation includes data preprocessing, model training, hyperparameter tuning via GridSearchCV, evaluation, and feature importance analysis.

### Features
- Data Preprocessing: Standardization and summary statistics.
- Model Training: Logistic Regression with ElasticNet penalty and GridSearchCV for hyperparameter optimization.
- Model Evaluation: Accuracy score and confusion matrix analysis.
- Feature Importance: Identification of key predictors using model coefficients.

### Results
The optimized model, with C=10 and l1_ratio=0.25, achieved 92.7% accuracy on the test set. Key predictors influencing spam classification were identified using feature importance analysis.

### Dependencies
- scikit-learn
- numpy
- pandas
- matplotlib
- ucimlrepo

