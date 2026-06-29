# 📊 Sales Prediction using Python & Machine Learning

A machine learning project that predicts future sales based on advertising spend across
TV, Radio, and Newspaper channels — delivering actionable insights for business marketing strategies.

## 📌 Project Overview

This project is part of my Data Science portfolio. It covers the full ML pipeline —
from exploratory data analysis and feature selection to model training, evaluation,
and business insight generation.

## 📂 Dataset

- **Source:** [Kaggle — Advertising CSV](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- **Features:** TV Ad Spend, Radio Ad Spend, Newspaper Ad Spend
- **Target:** Sales (in thousands)
- **Size:** 200 records

## 🔧 Tools & Libraries

- Python, Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🧪 ML Workflow

1. Exploratory Data Analysis (EDA)
2. Correlation & Pairplot Analysis
3. Feature & Target Split
4. Train/Test Split (80/20)
5. Feature Scaling (StandardScaler)
6. Model Training & Comparison
7. Business Insight — Ad Channel Impact Analysis
8. Hyperparameter Tuning (GridSearchCV)

## 🤖 Models Used

| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | 1.4608 | 1.7816 | 0.8994 |
| Ridge Regression | 1.4643 | 1.7872 | 0.8988 |
| Lasso Regression | 1.4613 | 1.7913 | 0.8983 |
| Random Forest | 0.6207 | 0.7688 | 0.9813 |
| Gradient Boosting | 0.6181 | 0.7295 | 0.9831 |

## 📈 Key Findings

- **TV** advertising has the strongest positive impact on sales
- **Radio** has a moderate but significant effect
- **Newspaper** spend shows minimal impact on sales outcomes
- Best model: **Gradient Boosting Regressor** with R² ≈ 0.97+

## 💡 Business Insight

Businesses looking to maximize sales should prioritize **TV and Radio** ad budgets
over Newspaper, as the data clearly shows diminishing returns on print advertising.

## 🚀 How to Run

1. Clone this repository
2. Open the `.ipynb` file in Google Colab
3. Upload `Advertising.csv` when prompted
4. Run all cells in order

## 👤 Author

**Fateen** — BS Computer Science, Air University Islamabad
- [GitHub](https://github.com/fatimafateen14/)
