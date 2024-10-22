# Credit Card Default Prediction
Predicting whether a customer will default on his/her credit card. Predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

## Algorithms Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting
- XG Boosting

## Conclusion
From all baseline model, Random forest classifier shows highest test accuracy and F1 score and AUC. Baseline model of Random forest and decision tree shows huge difference in train and test accuracy which shows overfitting. After cross validation and hyperparameter tunning, XG Boost shows highest test accuracy score of 87.10% and AUC is 0.874. Cross validation and hyperparameter tunning certainly reduces chances of overfitting and also increases performance of model.
