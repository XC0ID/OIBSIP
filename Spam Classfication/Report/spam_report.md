
---

# 📄 Project Report

```markdown
# 📊 Spam Email Classification Report

## 1. Introduction
Spam messages are unwanted communications that can be harmful or misleading. This project aims to build a machine learning model to automatically classify messages as spam or ham.

---

## 2. Objective
To develop a binary classification model that accurately detects spam messages using text data.

---

## 3. Dataset Description
- Source: `spam.csv`
- Type: Text dataset
- Features:
  - Label (spam/ham)
  - Message text

---

## 4. Methodology

### 4.1 Data Preprocessing
- Renamed columns for clarity
- Converted labels:
  - Ham → 0
  - Spam → 1
- Split dataset into training (80%) and testing (20%)

---

### 4.2 Exploratory Data Analysis
- Checked class imbalance
- Analyzed:
  - Message length
  - Word count
- Generated WordClouds to visualize common words

---

### 4.3 Feature Engineering
- Applied **TF-IDF Vectorization**
- Removed stopwords
- Limited features to top 10,000 words

---

### 4.4 Model Development

#### Model 1: Multinomial Naive Bayes
- Works well with text data
- Fast and efficient

#### Model 2: Logistic Regression
- Linear model
- Produces probability outputs
- Good interpretability

---

## 5. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

---

## 6. Results & Analysis

- Both models showed strong performance
- Logistic Regression provided better balance between precision and recall
- Naive Bayes was faster and suitable for baseline

### Visual Analysis:
- Confusion Matrix helped identify misclassifications
- ROC Curve showed model discrimination ability

---

## 7. Conclusion
The project successfully built a spam classifier using machine learning techniques. Both models performed well, with Logistic Regression slightly outperforming Naive Bayes in overall metrics.

---

## 8. Future Scope
- Implement deep learning models (LSTM, Transformers)
- Perform hyperparameter tuning
- Deploy model as an API or web application
- Use larger and more diverse datasets

---

## 9. References
- Scikit-learn Documentation
- Kaggle datasets
- NLP resources