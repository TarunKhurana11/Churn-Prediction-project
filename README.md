# Churn Prediction UI 

## Overview
Customer churn is a critical challenge for businesses. This project uses machine learning algorithms to analyze customer behavior and predict whether they are at risk of churning. The goal is to help businesses reduce churn rates by identifying at-risk customers and taking proactive measures.

## Features:
- Predicts whether a customer will churn based on their information.
- Users can input customer details like **age**, **contract type**, **internet service**, etc., into a form.
- Real-time predictions displayed using **Flask** and **Bootstrap** for the UI.
- The model has been tuned for high accuracy and efficiency using **XGBoost** and **Scikit-learn**.

## Technologies Used:
- **Python** for backend development.
- **Scikit-learn** and **XGBoost** for machine learning model.
- **Pandas**, **NumPy** for data manipulation.
- **Matplotlib** for visualizations (optional).

## 📂 Project Structure:-
📁 Churn-Prediction  
│── 📜 churn_prediction.py      # Main script for training & prediction  
│── 📜 preprocess_data.py       # Data cleaning and feature engineering  
│── 📜 model_evaluation.py      # Model performance analysis  
│── 📜 churn_model.pkl          # Saved trained model  
│── 📜 churn_dataset.csv        # Sample dataset (if public)  
│── 📜 accuracy_results.csv      # Model performance logs  
│── 📄 README.md                # Project documentation  
