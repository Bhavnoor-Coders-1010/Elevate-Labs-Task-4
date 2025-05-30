# Elevate-Labs-Task-4

Approach:
1. Imported important libraries and the dataset.
2. Explored dataset to check for any categorical columns (that need encoding).
3. Split the dataset into X and Y and standardized X (using StandardScaler() from sklearn) and encoded Y.
4. Further used train_test_split with test size of 20% and fit the LogisticRegression() model.
5. Reviwed the metrics - confusion matrix, classification report (with precision, recall, f1_score, accuracy), ROC-AUC-Score.
6. Plotted the ROC Curve.
7. Checked the roc-auc-score for different thresholds ranging from 0.1 to 0.9 (both included) - maximum score was found to be for 0.5

References:
1. Dataset - https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
2. https://www.google.com/search?q=where+to+import+logistic+regression+from+sklearn%3F&oq=where+to+import+logistic+regression+from+sklearn%3F&gs_lcrp=EgZjaHJvbWUyBggAEEUYOdIBCTI4NDkwajBqN6gCALACAA&sourceid=chrome&ie=UTF-8#:~:text=Logistic%20Regression%20can%20be%20imported%20from%20the%20sklearn.linear_model%20module.
3. https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html
4. https://www.geeksforgeeks.org/calculate-roc-auc-for-classification-algorithm-such-as-random-forest/
5. https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html
6. https://www.geeksforgeeks.org/what-is-the-default-threshold-in-sklearn-logistic-regression/
7. https://www.desmos.com/calculator (for graphs of sigmoid function and step function)
