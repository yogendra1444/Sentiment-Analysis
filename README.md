# Sentiment Analysis Using Machine Learning

## 📌 Project Overview

This project focuses on **Sentiment Analysis** using Machine Learning. The aim is to classify text into three categories:
- **Positive**
- **Negative**
- **Neutral**

We use the `Logistic Regression` algorithm and `TF-IDF` vectorizer for transforming text data into numerical format.

---

## 📂 Dataset

- The dataset contains labeled text data with sentiment labels: `-1` (Negative), `0` (Neutral), `1` (Positive).
- Preprocessing steps include:
  - Lowercasing
  - Removing stopwords, punctuation, and unwanted symbols

---

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (optional for visualization)
- Joblib (for saving model)

---

## 🚀 Model Building Steps

1. **Data Preprocessing**
   - Cleaned text data
   - Handled missing/null values

2. **Text Vectorization**
   - Used `TF-IDF` vectorizer to convert text into numerical format

3. **Model Training**
   - Trained `Logistic Regression` classifier
   - Achieved high accuracy (~92.5%)

4. **Evaluation**
   - Accuracy, precision, recall, f1-score

5. **Model Saving**
   - Saved the trained model and vectorizer using `joblib`


