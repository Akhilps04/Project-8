# Project-8
Random Forest Model for Employee Performance Prediction
# Project Overview
This project involves:
1.Preparing and pre-processing a dataset.
2.Addressing class imbalance using SMOTE.
3.Training a Random Forest Classifier with hyperparameter tuning.
4.Evaluating the model's performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
5.Visualizing feature importance, confusion matrix, and multi-class ROC curves.
# Model Details
1.Best Parameters (Random Forest)
2.n_estimators: 200
3.max_depth: 20
4.min_samples_split: 5
5.class_weight: Balanced
6.Performance
7.Accuracy: ~94.2%
8.Cross-Validation Accuracy: ~93.7% (Mean)
# Visualizations
1.Confusion Matrix Displays true positives, false positives, false negatives, and true negatives.
2.Feature Importance Highlights the top features influencing the Random Forest model.
3.ROC Curve Illustrates the true positive rate against the false positive rate for each class.
# Project Motivation
Employee performance is a critical factor in organizational success. Identifying high and low-performing employees using data-driven techniques helps in designing targeted training programs, improving team productivity, and enhancing overall efficiency. This project leverages machine learning to build a predictive model for employee performance, ensuring effective decision-making for human resource management.
# Challenges Faced
Class Imbalance: The target variable was imbalanced, which could bias the model predictions. We applied SMOTE to address this.
Feature Engineering: Transforming categorical variables into numerical values while preserving their interpretability.
# Results and Insights
The model achieved an accuracy of 94.2% on the test set.
The top three features influencing performance predictions were:
a.Training Outcome
b.Years of Experience
c.Job Role
The confusion matrix revealed that Class 2 was frequently misclassified as Class 3, suggesting overlap in feature space.
# Future Scope
Real-time Predictions: Integrate the model with an HR management system.
Explainability: Add tools like SHAP or LIME to explain model predictions.
Generalization: Train the model on datasets from multiple organizations to improve robustness.

