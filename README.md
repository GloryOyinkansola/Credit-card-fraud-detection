# Credit Card Fraud Detection Project
### A Machine Learning Classifier that classifies a credit card transaction as fraudulent or non-fradulent

In 2020, Nigerian banks lost 3.5billion to fraud related cases. It is therefore important that financial institutions  are able to recognize fraudulent credit card transactions so that customers are not charged for items they did not purchase. I worked on an algorithm, which could classify a transaction as fraudulent or non-fraudulent.

The dataset was gotten from kaggle and it contains transactions made with credit cards in September 2013 by European cardholders.

The dataset is highly unbalanced, the positive class (frauds) account for only 0.172% of all transaction. This problem was solved using the Random undersampling and oversampling approach

Due to confidentiality issues, the original features were not provided, but were  scaled using PCA transformation. 

Four classifiers: Logistic regression, KNeighbors classifier, SupportVector classifier, and Decision tree classifier were used.

In the end, it can be concluded that the logistic regression performed the best on the oversampled dataset and will be the best model for fraud detection.

