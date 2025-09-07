# axia-cohort8-loan-model-oreoluwa
Loan Default Prediction Project for Axia Cohort 8
# Loan Default Prediction Project

👤 **By: Oreoluwa Agbeke Ogundele**  
🎓 **Axia Cohort 8**  
🔗 [LinkedIn](https://linkedin.com/in/oreoluwa-agbeke-ogundele)  
📧 oreoluwaogundele3@gmail.com  
📍 Nigeria

🎯 **Project Goal**:  
Predict whether a customer will default on a loan using their **demographics**, **loan details**, and **past repayment behavior**.

📊 **Key Insight**:  
**Past late repayment behavior** (e.g., `avg_days_late`, `late_repayment_rate`) is the strongest predictor of default — stronger than age, job type, or loan amount.

> 💡 *"Past behavior is the best predictor of future risk."*

## 📁 Project Files

| File | Description |
|------|-------------|
| `loan_default_analysis.ipynb` | Full analysis: data cleaning, EDA, modeling, and feature importance |
| `cleaned_loan_data.csv` | Cleaned and merged dataset for Power BI or further analysis |

## 🧪 Model Performance

- **Best Model**: Logistic Regression
- **ROC-AUC Score**: 0.709
- **Top Feature**: `avg_days_late`
- **Recall for Defaults**: 30% → room for improvement

## 📊 Feature Importance

The most important predictors of loan default:
1. `avg_days_late`  
2. `late_repayment_rate`  
3. `total_past_loan_amount`

👉 See notebook for full permutation importance chart.

## 📚 Technologies Used

- Python, pandas, NumPy
- Scikit-learn (modeling & imputation)
- Matplotlib & Seaborn (visualization)
- Jupyter Notebook

Thank you for reviewing my work.  
— **Oreoluwa Agbeke Ogundele**
