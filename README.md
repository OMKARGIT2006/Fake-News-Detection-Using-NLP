# Fake-News-Detection-Using-NLP
Detects fake news using NLP and machine learning. Includes text cleaning, TF-IDF feature extraction, and classification with Logistic Regression. Achieved 99% accuracy. Future work includes SVM, LSTM, and BERT models.


# 📰 Fake News Detection with NLP & Machine Learning

This project is all about spotting fake news using text analysis and machine learning. It takes raw news articles, cleans them up, turns them into numbers using TF-IDF, and trains a model to figure out if the article is real or fake.

## 📦 Dataset
The dataset includes news articles labeled as either *REAL* or *FAKE*. It was taken from a public source (like Kaggle) and contains a mix of headlines, reports, and more.

## 🛠️ What I Did
- Cleaned the text: lowercased, removed punctuation, URLs, and stopwords
- Used **TF-IDF** to turn text into feature vectors
- Trained a **Logistic Regression** model
- Evaluated it using accuracy, precision, recall, and F1-score

## ✅ Results
The model performed really well — about **99% accuracy**.  
Here’s a quick look:

FAKE — Precision: 1.00, Recall: 0.99, F1: 0.99

REAL — Precision: 0.99, Recall: 1.00, F1: 0.99
