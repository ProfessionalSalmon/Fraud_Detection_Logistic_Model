# Credit Card Fraud Detection predicted by Logistic Regression Model

Thanks to dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)!

In this notebook, I have created a Logistic Regression model on imbalanced dataset to classify transactions as either fraud or non-fraud. This model is evaluated by Area under the Precision-Recall curve (PR AUC) and received a score of approximately 0.97 due to undersampling technique. This scoring metric is used because it is sensitive to imbalanced dataset where positive class is rare and cost of false positive is also high.

![picture](/pr-auc.png)


