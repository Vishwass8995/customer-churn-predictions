# 📉 Customer Churn Prediction

Predicts which telecom customers are likely to leave using ML.

## 📊 Results
| Model | Accuracy | AUC Score |
|---|---|---|
| Logistic Regression | ~80% | ~0.85 |
| Random Forest (baseline) | ~85% | ~0.88 |
| **Random Forest (GridSearchCV)** | **~87%** | **~0.91** ✅ |

## 🔍 Key Business Insights
- Month-to-month contract customers churn at 3x higher rate
- New customers (< 12 months) are highest risk group
- Fiber optic internet users churn more than DSL users
- High monthly charges + short tenure = highest churn risk

## ⚙️ New Skill: GridSearchCV
Used GridSearchCV with 5-fold cross-validation to automatically
find optimal hyperparameters, improving accuracy over baseline.

## 🛠️ Tech Stack
Python · Pandas · Scikit-learn · Matplotlib · Seaborn

## 👤 Author
**Vishwas Sharma** — Aspiring Data Scientist
