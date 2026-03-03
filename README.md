# 🏠 House Price Prediction - Regression Project

## 📌 Project Overview
This project predicts house prices using machine learning regression models.  
The goal was to compare multiple models and build a production-ready pipeline.

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## 📊 Models Used
1. Linear Regression (Baseline)
2. Random Forest Regressor
3. Gradient Boosting Regressor (Best Model)

---

## 📈 Results

| Model | RMSE |
|-------|------|
| Linear Regression | ~0.016 |
| Random Forest | ~0.011 |
| Gradient Boosting | ~0.010 |

Gradient Boosting performed the best with stable cross-validation performance.

---

## 🔄 Workflow
- Data Cleaning
- Feature Engineering
- Model Training
- Cross Validation
- Pipeline Creation
- Model Saving with Joblib

---

## 💾 Final Model
The final production-ready model was saved as:

house_price_model.pkl

It includes:
- Preprocessing
- Model
- Ready-to-use prediction pipeline

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Try XGBoost / LightGBM
- Deploy as API using FastAPI