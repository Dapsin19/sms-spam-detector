# 📬 SMS Spam Detector

This project uses Natural Language Processing (NLP) and Logistic Regression to classify SMS messages as spam or ham (not spam).

## 🚀 Features
- EDA on SMS Spam Collection Dataset
- CountVectorizer for text feature extraction
- Logistic Regression for classification
- Custom message prediction
- Model saving and loading

## 📂 Files Included
- `spam_classifier_model.pkl`: Trained Logistic Regression model
- `spam_vectorizer.pkl`: Fitted CountVectorizer
- `spam_classifier.ipynb`: Colab notebook with all code and explanations

## 📊 Dataset
- [UCI SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

## ✨ Try It Yourself
Load the model and vectorizer, and predict new messages like:
```python
msg = ["Hello, you've won a free cruise!"]
vec = vectorizer.transform(msg)
model.predict(vec)  # [1] means spam
