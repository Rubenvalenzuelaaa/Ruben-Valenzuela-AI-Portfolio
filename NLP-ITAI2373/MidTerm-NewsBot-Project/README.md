# 📰 Mid-Term Group Project: NewsBot Intelligence System

## 📌 Problem Statement
The objective of this project was to develop an **NLP-based NewsBot** capable of:
1. Classifying news articles by **topic**.
2. Detecting **bias** in the content.
3. Performing **sentiment analysis** to determine overall tone.

The project was a **group collaboration** between **Rubén Valenzuela** and **Miguel Mora** as part of the **ITAI2373 – Natural Language Processing** course.

---

## 🛠 Approach & Methodology

### **1. Data Preprocessing**
- Collected and cleaned a dataset of news articles.
- Tokenization, stopword removal, and lemmatization.
- Converted text into numerical representations using **TF-IDF**.

### **2. Sentiment & Bias Detection**
- Applied **VADER** for sentiment polarity classification (positive, neutral, negative).
- Implemented bias detection by analyzing lexical indicators and subjectivity scores.

### **3. News Classification**
- Trained supervised ML models (**Naive Bayes**, **Logistic Regression**) for topic classification.
- Evaluated models using accuracy, precision, recall, and F1-score.

---

## 📊 Results
- Achieved **85% accuracy** in sentiment classification.
- Bias detection correctly flagged articles with high subjectivity.
- News classification models performed best with **Logistic Regression** on TF-IDF features.

---

## 🎯 Learning Outcomes
- Learned to integrate **multiple NLP tasks** (sentiment, bias, classification) into a single pipeline.
- Gained experience in **model evaluation** and **comparative analysis**.
- Understood real-world applications of NLP for **media monitoring and analysis**.

---

## 📦 Requirements
```bash
pip install pandas numpy scikit-learn nltk spacy vaderSentiment textblob
python -m spacy download en_core_web_sm
