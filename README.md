# 📊 Customer Churn Prediction

## 🎯 Project Overview
Predicting which telecom customers are likely to churn 
using machine learning models and visualizing insights 
through an interactive Tableau dashboard.

## 📁 Dataset
- **Source:** Telco Customer Churn — IBM Dataset (Kaggle)
- **Rows:** 7,032 customers
- **Columns:** 21 features
- **Target:** Churn (Yes/No)

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python | Data processing & ML |
| pandas | Data cleaning & EDA |
| matplotlib & seaborn | Data visualization |
| scikit-learn | ML models |
| XGBoost | Best performing model |
| SMOTE | Handling class imbalance |
| Tableau Public | Interactive dashboard |
| Jupyter Notebook | Development environment |

## 📋 Project Steps
1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Feature encoding and scaling
5. Handling class imbalance using SMOTE
6. Model building and evaluation
7. Tableau dashboard creation

## 🤖 Models & Results
| Model | Accuracy | Recall | ROC-AUC |
|-------|----------|--------|---------|
| Logistic Regression | ~80% | ~81% | ~88% |
| Random Forest | ~82% | ~80% | ~90% |
| XGBoost | ~83% | ~82% | ~91% |

## 💡 Key Insights
- Month-to-month contract customers churn the most
- Churned customers pay ~20% higher monthly charges
- Customers with low tenure (1-2 months) are most likely to churn
- Long-term customers (60+ months) rarely churn

## 📊 Tableau Dashboard
🔗 [View Live Dashboard](https://public.tableau.com/views/Customer_Churnpredication/CustomerChurnAnalysisDashboard)

## 📂 Files in Repository
- `churn_project.ipynb` — Complete Jupyter Notebook
- `churn_tableau.csv` — Cleaned dataset used for Tableau

## 🚀 How to Run
1. Clone this repository
2. Download the dataset from Kaggle
3. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
4. Open `churn_project.ipynb` in Jupyter or VS Code
5. Run all cells in order
