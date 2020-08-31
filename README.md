# Sales Forecast Engine
The repository makes use of two files:
1. 'sales_pipeline.csv' - This consists of all sales related data
2. 'interactions.csv' - This file consists of all interactions between the sales-person and the customer

There are 5 different jupyter notebooks.
1. EDA + ML - This notebook has the model built only on the numeric features for prediction. It also contains EDA of the entire dataset.

2. NLP Model - This model uses text+numeric features for classification. It also contains the EDA analysis of all text features. Model used - Multinomial Naive Bayes using TFIDF and BOW Vectorizer

3. Logistic Model - Uses a Logistic Regression Model for classification. Hyperparameter tuning done. Using TFIDF and BOW Vectorizer

4. All Numeric Training - This consists of model building for Numeric Features for prediction. Algorithms used - KNN, GBM, Ridge, Lasso, SVR, Randm Forests

5. All Predictions - This notebook contains all the models used for classification. All results are properly documented.

Thanks
