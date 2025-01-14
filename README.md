**Obesity Classification and Regression Analysis**

This project focuses on classifying individuals' obesity levels based on demographic and lifestyle factors. While the primary objective is classification, regression analysis was also explored as an additional perspective for understanding the data.

**Project Overview**

**Primary Goal:**

To build and evaluate machine learning models for obesity classification.

**Secondary Goal:**

To experiment with regression models to gain additional insights.

**Dataset:** 

A dataset containing demographic, lifestyle, and health-related variables was used for analysis.

**Key Findings**

Best Performing Models:

The optimized Random Forest and optimized Support Vector Machine (SVM) achieved the highest accuracy of 96.74%, with exceptional precision, recall, and F1-scores across all classes.
Both models exhibited robustness, as demonstrated by their confusion matrices, with very few misclassifications and high true positive rates.
The Random Forest with top features showed slightly better class-specific precision and recall, making it the preferred model.
Other Models:

Logistic Regression and k-Nearest Neighbors (k-NN) performed adequately but were outperformed by the Random Forest and SVM in terms of all evaluation metrics.

Evaluation Summary:

The performance of all models was visualized using a bar plot, highlighting the superior accuracy, F1-score, precision, and recall of the optimized Random Forest and SVM models.
The Random Forest classifier achieved a training accuracy of 100% and a test accuracy of 96.74%, demonstrating excellent generalization without overfitting.
The Area Under the Curve (AUC) scores for the Random Forest were consistently higher than other models, emphasizing its ability to distinguish between different classes.
Interpretability and Model Trade-offs

Random Forest with Top Features:

Balances high accuracy with reasonable interpretability due to the reduced number of features.
Provides feature importance scores, aiding in understanding the model's decision-making process.
Recommended model due to its excellent accuracy, AUC, and interpretability.

SVM:

Offers high accuracy but is challenging to interpret due to complex kernel functions and decision boundaries.

Logistic Regression:

The most interpretable model, with feature importance directly derived from coefficients. However, it lags behind in accuracy.

k-NN:

Simple to understand for small datasets but becomes less interpretable as the number of neighbors increases.
