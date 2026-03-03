# 🏠 House Price Prediction - Regression Project

## 📌 Project Objective
The goal of this project was to predict house prices using supervised machine learning regression models and compare their performance using RMSE.

---

## 📊 Dataset
- Tabular housing dataset
- Mixed numerical & categorical features
- Target variable was log-transformed to reduce skewness

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Handled missing values
- Removed highly null columns
- Ensured consistent data types

### 2️⃣ Feature Engineering
- Log transformation applied to target variable
- Encoded categorical features (converted to numerical)
- Verified skewness reduction

### 3️⃣ Model Training

#### Baseline Model:
- Linear Regression

#### Advanced Models:
- Random Forest Regressor
- Gradient Boosting Regressor

---

## 📈 Model Performance (RMSE)

| Model | RMSE |
|-------|------|
| Linear Regression | ~0.016 |
| Random Forest | ~0.011 |
| Gradient Boosting | **~0.010** |

Cross-validation confirmed stability of Gradient Boosting model.

---

## 🧠 Final Model

The final production-ready model:
- Gradient Boosting Regressor
- Wrapped inside a Scikit-learn Pipeline
- Saved using Joblib

File:
house_price_model.pkl

---

## 🏗 Key Learnings

- Importance of cross-validation
- Tree-based models outperform linear models for complex tabular data
- Pipeline ensures reproducibility and production readiness
- RMSE is a reliable regression evaluation metric

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try XGBoost / LightGBM
- Deploy model using FastAPI
- Add model explainability (SHAP)

---

## 👨‍💻 Author

Abhihail Jacob  
Aspiring Python AI Engineer