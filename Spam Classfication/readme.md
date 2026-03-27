# 📧 Spam Email Classification

## 📌 Overview
This project focuses on building a **Spam Email Classifier** using Machine Learning techniques. The goal is to classify emails/messages as:

- **Ham (0)** → Legitimate message  
- **Spam (1)** → Unwanted / promotional message  

---

## 📂 Dataset
- File: `spam.csv`
- Contains labeled SMS/email messages
- Columns:
  - `label`: spam / ham
  - `text`: message content

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- WordCloud
- Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Loading
- Dataset loaded using pandas
- Columns renamed for clarity

### 2. Exploratory Data Analysis (EDA)
- Class distribution visualization
- Message length & word count analysis
- WordCloud for spam vs ham messages

### 3. Preprocessing
- Label encoding (ham → 0, spam → 1)
- Train-test split (80/20)
- Text vectorization using **TF-IDF**

### 4. Model Building
Two models were trained:
- **Multinomial Naive Bayes**
- **Logistic Regression**

### 5. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### 6. Visualization
- Confusion Matrix
- ROC Curve
- Model comparison charts

---

## 📊 Results
- Both models performed well on text classification
- Logistic Regression provided strong overall balance
- Naive Bayes was faster and efficient for sparse data

---

## 🚀 How to Run

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud

# Run notebook
jupyter notebook spam_classification.ipynb