# =========================
# 📊 Advertising Dataset — Regression Analysis Report
# =========================

## 1. Introduction
This project focuses on analyzing the relationship between advertising expenditures and product sales. The aim is to build predictive models that estimate sales based on marketing budgets.

---

## 2. Objective
- Understand the impact of different advertising channels
- Build regression models to predict Sales
- Compare model performance

---

## 3. Dataset Description
The dataset contains 200 observations with the following variables:
- TV: Advertising budget spent on TV
- Radio: Advertising budget spent on Radio
- Newspaper: Advertising budget spent on Newspaper
- Sales: Units sold

---

## 4. Data Preprocessing
- Removed unnecessary index column
- Checked for missing values (none found)
- Standardized features for certain models (Ridge Regression)
- Split dataset into training (80%) and testing (20%)

---

## 5. Exploratory Data Analysis (EDA)
- Histograms showed distribution of features
- Correlation heatmap indicated:
  - Strong correlation: TV → Sales
  - Moderate correlation: Radio → Sales
  - Weak correlation: Newspaper → Sales
- Scatter plots confirmed linear relationships

---

## 6. Models Implemented
1. Linear Regression
2. Ridge Regression
3. Random Forest Regressor
4. Gradient Boosting Regressor

---

## 7. Model Evaluation Metrics
- R² Score (Model Accuracy)
- RMSE (Error Magnitude)
- MAE (Average Error)

---

## 8. Results & Comparison
- Linear Regression performed well as baseline
- Ridge improved stability with regularization
- Random Forest captured non-linear patterns
- Gradient Boosting achieved highest accuracy

---

## 9. Feature Importance
- TV advertising is the most influential factor
- Radio contributes moderately
- Newspaper has minimal effect

---

## 10. Conclusion
- Advertising spend significantly affects sales
- Machine learning models can predict sales effectively
- Ensemble methods outperform linear approaches

---

## 11. Future Work
- Hyperparameter tuning
- Try advanced models (XGBoost, Neural Networks)
- Use larger datasets for better generalization
