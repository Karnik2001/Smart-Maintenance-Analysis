# 🛠️ Smart Maintenance Analysis using Machine Learning & Explainable AI
## 📌 Overview

This project focuses on building a predictive maintenance system using machine learning models to classify maintenance priority levels based on operational and sensor data.
In addition to predictive modeling, the project integrates Explainable AI (XAI) techniques to interpret model decisions, making the system more transparent and actionable for real-world industrial applications.

## 📊 Dataset Description

The dataset contains key operational and maintenance-related features, including:

- Temperature (°C)
- Vibration (mm/s)
- Pressure (Bar)
- Acoustic Levels (dB)
- Inspection Duration (minutes)
- Downtime Cost (USD)
- Technician Availability (%)
- Failure Probability
  
🎯 Target Variable
Maintenance Priority (Multi-class classification)

## ⚙️ Machine Learning Models Used

The following models were implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- AdaBoost Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)
- Gaussian Naive Bayes
- Multi-Layer Perceptron (MLP)
- XGBoost Classifier
  
## 📈 Model Performance

Models were compared using accuracy and classification metrics to identify the best-performing algorithm for maintenance prediction.
Ensemble methods like Random Forest, Gradient Boosting, and XGBoost typically showed strong performance due to their ability to handle nonlinear relationships.

## 🔍 Explainable AI (XAI)

To ensure interpretability and transparency, multiple XAI techniques were applied:

🔹 Global Interpretability
- Permutation Feature Importance
- SHAP (SHapley Additive Explanations)
- Feature importance ranking
- Summary plots for global impact
- Dependence plots for feature interaction insights
  
🔹 Local Interpretability
- LIME (Local Interpretable Model-Agnostic Explanations)
- Explains individual predictions
- SHAP Force Plots
- Visual breakdown of how features contribute to a specific prediction
  
🔹 Counterfactual Explanations
- Generated alternative scenarios to:
- Show how predictions can change
- Provide actionable insights for maintenance decisions
  
## 🧠 Key Insights
- Identified critical drivers of equipment failure risk
- Provided instance-level explanations for decision-making
- Enabled what-if analysis through counterfactuals
- Improved trust and transparency in model predictions
  
## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- SHAP, LIME (XAI tools)
- Jupyter Notebook

## 📌 Applications
- Predictive maintenance in manufacturing
- Industrial equipment monitoring
- Cost reduction through early failure detection
- Decision support systems for operations
  
## 📎 Future Improvements
- Hyperparameter tuning
- Model deployment (Flask / Gradio)
- Real-time monitoring system
Advanced SHAP dashboards for business users
