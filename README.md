# Predicting Corporate Performance using Machine Learning

This project explores how machine learning can be applied to analyze the determinants of corporate profitability, using **Return on Assets (RoA)** as the target variable.

### Objectives
- Identify key financial ratios that influence corporate performance.
- Compare multiple regression models (OLS, Ridge, Lasso, Decision Tree).

### Techniques
- **Linear Regression (OLS)**
- **Ridge & Lasso Regression**
- **Decision Tree Regression**

### Results
| Model | Mean MAE | Std MAE | R² | Comment |
|-------|-----------|---------|----|----------|
| OLS | 8.25 | 2.40 | 0.13 | Baseline |
| Ridge | **7.82** | **1.84** | 0.14 | Best model |
| Lasso | 8.00 | 2.25 | 0.12 | Feature selection |
| Decision Tree | — | — | -1.47 | Underfitting |

### Key Insights
- Tangibility and Current Ratio have a positive, significant effect on RoA.  
- ROI shows a negative relationship, indicating diminishing returns at higher investment levels.  
- Ridge regression balances overfitting and interpretability best.

### Tools & Libraries
`Python`, `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `statsmodels`

---

👨‍💼 **Author:** Rahil Shah  
MS Finance (STEM) | Fordham University  
[LinkedIn](https://www.linkedin.com/in/rahil-shah52)
