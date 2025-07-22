# Bank Marketing Campaign Success Prediction 🏦📈

This project uses machine learning to predict whether a customer will subscribe to a term deposit based on data from a Portuguese bank's telemarketing campaign. It includes full steps from data loading to model evaluation and comparison.

## 🔍 Problem Statement
Banks often run telemarketing campaigns to sell term deposits. However, cold-calling leads to a very low success rate. This project aims to build a predictive model that identifies likely responders, helping to improve campaign efficiency.

## 📊 Dataset
- **Source**: [Kaggle - Bank Marketing Dataset](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/data)
- **Instances**: 39,211 training samples and 10,000 test samples
- **Features**: 16 (categorical and numerical)
- **Target**: `y` (whether the client subscribed to a term deposit)

## 🛠️ Technologies Used
- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🧠 ML Models Compared
- Logistic Regression
- SGD Classifier
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier

## 📈 Metrics Evaluated
- F1-score
- Confusion Matrix

## 📌 Key Insights
- Job type, contact method, and month were important features.
- Imbalanced target class requires attention (e.g., SMOTE, class weights).
- Random Forest and XGBoost performed better than basic classifiers.
