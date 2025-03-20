## Fraud Detection Model Training

# Overview

This project trains a fraud detection model using a Hybrid Approach that combines Isolation Forest (IF) for anomaly detection and XGBoost for supervised learning. The model is trained on a bank transactions dataset and aims to improve fraud detection accuracy.

# Dataset

The dataset consists of transaction records labeled as fraudulent (1) or legitimate (0).

Preprocessing includes feature scaling and handling class imbalance.

# Model Training Steps

Data Preprocessing

Scale features using StandardScaler.

Unsupervised Learning with Isolation Forest

Detect anomalies using Isolation Forest.

Assign anomaly scores to the dataset.

Supervised Learning with XGBoost

Train XGBoost on labeled anomalies from Isolation Forest.

Optimize hyperparameters for better fraud detection.

# Model Evaluation

Compute Precision, Recall, F1-score.

Measure AUC-ROC Score for model performance.

# Results

✅ Accuracy: 99%
✅ Precision for Fraud Cases: 97%
✅ Recall for Fraud Cases: 90%
✅ AUC-ROC Score: 0.9490
