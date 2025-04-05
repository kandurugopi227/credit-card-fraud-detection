# credit-card-fraud-detection
A machine learning project for detecting fraudulent credit card transactions using Python and Scikit-learn. This repository covers the full pipeline—from exploratory data analysis (EDA) and handling class imbalance (SMOTE/ADASYN) to training models like Logistic Regression, Random Forest, and XGBoost. Key focus areas include optimizing precision-recall metrics to reduce false positives and deploying scalable solutions (e.g., Flask API). The project emphasizes real-world applicability, with detailed notebooks on feature engineering, model evaluation (ROC-AUC, F1-score), and benchmarking against anomaly detection methods (Isolation Forest, Autoencoders). Ideal for learning fraud detection techniques or integrating into financial systems.

Credit Card Fraud Detection using Machine Learning
Python Scikit-learn Pandas
A machine learning project to detect fraudulent credit card transactions using EDA, regression, and ensemble methods.

📌 Project Overview
This project aims to build a robust fraud detection system using:
Exploratory Data Analysis (EDA) to identify transaction patterns.
Machine Learning Models: Logistic Regression, Decision Trees, Random Forest, and more.
Handling Class Imbalance with SMOTE/ADASYN.
Model Evaluation using precision, recall, F1-score, and ROC-AUC.

📂 Dataset
Source: Kaggle Credit Card Fraud Dataset
Features: Time, Amount, V1-V28 (anonymized PCA components).
Class Distribution: Highly imbalanced (fraud = 0.172% of transactions).

📊 Techniques Used
1. Exploratory Data Analysis (EDA)
Visualized transaction distributions (time/amount).
Analyzed correlations between PCA features.
Detected outliers using box plots and Z-score.

2. Machine Learning Models
Model	Precision	Recall	F1-Score	ROC-AUC
Logistic Regression	0.85	0.76	0.80	0.97
Decision Tree	0.88	0.81	0.84	0.98
Random Forest	0.92	0.89	0.90	0.99

4. Handling Class Imbalance
SMOTE: Synthetic Minority Oversampling Technique.
Class Weighting: Adjusted weights in Random Forest.

📧 Contact
For questions, email:kundurugopi5@gamil.com
