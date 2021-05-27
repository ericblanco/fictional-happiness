# fictional-happiness
Network Intrusion Detection System.
This is a classification problem where the model classifies the incoming connection request into
two categories: normal (1) and anomaly (0). I used the KDD dataset available online which
comprised 42 features and one target column. There was no missing value in the dataset, so I
moved to the feature engineering part where I scaled the features and encoded categorical
attributes into numerical. Then I did the feature selection by using a recursive feature elimination
method. In the end, I partitioned the dataset and trained on four algorithms Decision Tree, KNN,
logistic regression and Naive bayes. I got 99.6 accuracy on the decision tree. So, I saved that
model and deployed it using flask.
