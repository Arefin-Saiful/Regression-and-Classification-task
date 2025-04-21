🧠 Regression and Classification Models for Predictive Analytics
This repository contains the code and report for a Machine Learning coursework project focused on two classic supervised learning problems:

🏡 Housing Price Regression using the California Housing dataset.

🚢 Titanic Survival Classification using the Titanic passenger dataset.

The project explores multiple algorithms, evaluates them on standard metrics, and selects the most effective models through experimentation and tuning.

📊 Project Overview
💼 Regression Task
Objective: Predict median house prices based on demographic and housing-related features.

Dataset: California Housing Dataset

Best Model: XGBoost Regressor (R² = 0.7017, MSE = 4.77B)

Other Models: Random Forest, Linear Regression, SVR, Decision Tree

Key Techniques: Feature engineering, One-hot encoding, Min-Max scaling, Hyperparameter tuning via GridSearchCV

✅ Classification Task
Objective: Predict survival outcomes for Titanic passengers.

Dataset: Titanic Dataset

Best Model: Tuned Random Forest Classifier (Accuracy = 85%)

Other Models: XGBoost Classifier, Logistic Regression

Key Techniques: Feature engineering (Title, FamilySize, IsAlone), Handling missing data, One-hot encoding, RandomizedSearchCV

📈 Evaluation Metrics
Regression:
Mean Squared Error (MSE)

R² Score

Classification:
Accuracy

Precision, Recall, F1-Score

🛠️ Tools & Libraries
Python (3.8+)

Scikit-learn

XGBoost

Pandas, NumPy, Matplotlib, Seaborn
