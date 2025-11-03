# Chronic_Kidney_Disease_Prediction_System
🩺 Chronic Kidney Disease (CKD) Prediction System

A machine learning–based prediction system that detects whether a patient is likely to have Chronic Kidney Disease (CKD) based on clinical and biological parameters.
This project demonstrates an end-to-end ML workflow — data preprocessing, model training, evaluation, and model saving for deployment.

📘 Project Overview

The project aims to build a predictive model that classifies patients as CKD or Not CKD, using features like blood pressure, albumin, hemoglobin, and diabetes status.
It compares multiple machine learning models and selects the one with the best performance.

🧩 Dataset

File: kidney_disease.csv
Samples: 400
Features: 24 clinical and biological attributes
Target: CKD (1) or Not CKD (0)

Source: UCI Machine Learning Repository - Chronic Kidney Disease Dataset

⚙️ Workflow

Data Preprocessing

Handle missing values

Encode categorical variables

Normalize numeric data

Model Training

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine

K-Nearest Neighbors

XGBoost

Evaluation

Accuracy

Confusion Matrix

Precision, Recall, F1-score

Model Saving

Best model saved using Pickle

Ready for web deployment (Streamlit)

🧠 Model Performance
Model	Accuracy
Logistic Regression	96%
Decision Tree	99%
Random Forest	100%
SVM	97%
KNN	97%
XGBoost	99%

✅ Best Model: Random Forest (High Accuracy and Stability)

💾 Deployment

The model is deployed using Streamlit for real-time predictions.
Users can input patient data and instantly receive a CKD/Not CKD prediction.

To run:

streamlit run app.py

🧰 Technologies Used

Python

Pandas, NumPy

Scikit-learn, XGBoost

Matplotlib, Seaborn

Streamlit

Pickle

📈 Results

Models achieved 96–100% accuracy.

Demonstrated complete ML workflow from preprocessing to deployment.

Helps detect CKD early for timely medical intervention.
