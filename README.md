# Capstone_Project
 Gender Prediction using Dental Metrics for forensic dentistry applications.
 projects follow a structured data science pipeline including EDA, feature engineering, model building, hyperparameter tuning, and evaluation.

Project 1: CLV Prediction
Objective:
Predict the Customer Lifetime Value (CLV) using various regression models to help insurance companies optimize their marketing strategies.

Dataset:
Records: 9,134
Features: 24 (Customer demographics, policy details, vehicle information, claim history, etc.)
Techniques Used:
✔ Exploratory Data Analysis (EDA)
✔ Feature Selection & Engineering
✔ Model Training (Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, AdaBoost)
✔ Hyperparameter Tuning using GridSearchCV
✔ Model Evaluation (R² Score, MAE, RMSE)

📝 Best Model: Random Forest (R² = 0.9098)

Project 2: Gender Prediction Using Dental Metrics
Objective:
Classify gender based on dental measurements to aid forensic investigations.

Dataset:
Features: Dental measurements (width, index, intraoral & cast metrics)
Target: Gender (Male/Female)
Techniques Used:
✔ Data Preprocessing (Handling missing values, encoding, normalization)
✔ Exploratory Data Analysis (Correlation analysis, feature importance)
✔ Model Training (Logistic Regression, Decision Tree, Random Forest, XGBoost)
✔ Evaluation (Confusion Matrix, Classification Report, ROC-AUC Score)

Tools & Libraries
Python (pandas, numpy, seaborn, matplotlib, sklearn)
Google Colab / Jupyter Notebook
Scikit-Learn, XGBoost
GridSearchCV for Hyperparameter Tuning
