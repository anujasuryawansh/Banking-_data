# Banking-_data
Logistic Regression model on the Bank Marketing dataset.

To improve the model’s ability to detect actual subscribers (class 1):

Handle Class Imbalance:

✅ Use SMOTE (Synthetic Minority Oversampling Technique)

✅ Try class_weight='balanced' in LogisticRegression

✅ Use undersampling of the majority class

Model Enhancements:

Try tree-based models like Random Forest, XGBoost, which handle imbalance better.

Tune threshold using ROC curve or Precision-Recall curve for optimal F1.

Evaluation Metrics:

Use ROC-AUC, PR-AUC, and F1-score for class 1 instead of overall accuracy.

Accuracy is misleading when the dataset is imbalanced.

Business Perspective:

Even if the number of predicted subscribers is small, these leads are valuable.

Reducing false negatives (missing potential customers) can directly improve campaign ROI.

