Fraud Detection System
An AI-powered fraud detection system that automatically identifies fraudulent online transactions using machine learning and provides real-time fraud risk assessment through a Flask-based web app.


Overview
Objective: Detect fraudulent transactions to enhance financial security.

Dataset: https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset

Models Used: Logistic Regression, Random Forest, XGBoost

Best Performer: Random Forest achieved the best balance between recall and precision.

Deployment: Flask API + Web frontend (HTML, CSS, JS).


Features
Handles imbalanced data using SMOTE and class weights.

Evaluated with Precision, Recall, F1-score, and PR-AUC.

Provides fraud probability, risk level, and recommendations.

User-friendly web interface for entering transaction details.


How It Works
User enters transaction details (amount, type, balances).

Flask backend sends data to the trained ML model.

Model predicts fraud probability and returns the result.

Frontend displays the risk level (Safe / Fraud) with details.


Results
Logistic Regression → Baseline model

XGBoost → Strong performance but required more tuning

Random Forest → Best results with high recall and stable precision


Tech Stack

Python (Pandas, Scikit-learn, XGBoost, Imbalanced-learn)

Flask (Backend API)

HTML, CSS, JavaScript (Frontend)

Joblib/PKL for model saving and loading

          
