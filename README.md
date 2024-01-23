# credit-risk-classification

Step 1: Project Overview

This analysis is part of the George Washington University Data Analytics Bootcamp project.
The goal is to predict loan status using logistic regression applied to lending data.

Step 2: Data Preparation

The lending data is loaded from the "Resources" folder into a Pandas DataFrame.
Labels (y) are created from the "loan_status" column, and features (X) are extracted from the remaining columns.

Step 3: Data Exploration

The balance of the labels variable (y) is checked using the value_counts function.

Step 4: Data Splitting

The data is split into training and testing datasets using the train_test_split function.

Step 5: Original Logistic Regression Model

Logistic regression model is instantiated and fitted using training data.
Predictions are made on the testing data, and model performance is evaluated.
Accuracy score, confusion matrix, and classification report are generated.

Step 6: Analysis of Original Model

Accuracy score of 99.18% is achieved, indicating high accuracy.
Confusion matrix reveals low false positives and false negatives.
Classification report demonstrates high precision, recall, and F1-score.

Step 7: Data Resampling

RandomOverSampler is used to resample the data, ensuring equal data points for both labels.
Step 8: Logistic Regression Model with Resampled Data

A new logistic regression model is fitted using the resampled training data.
Predictions are made on the testing data, and model performance is evaluated.
Accuracy score, confusion matrix, and classification report are generated.

Step 9: Analysis of Resampled Model

Resampled model shows improved accuracy of 99.38%.
Confusion matrix indicates continued low misclassifications.
Classification report demonstrates high precision, recall, and F1-score.

Step 10: Conclusion

The logistic regression model, especially when trained on oversampled data, proves highly effective in predicting loan status.
The project showcases proficiency gained through the George Washington University Data Analytics Bootcamp, providing robust insights into data analysis and predictive modeling.
