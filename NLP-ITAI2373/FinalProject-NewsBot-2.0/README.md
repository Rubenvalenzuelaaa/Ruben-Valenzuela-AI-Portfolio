# 📰 Final Project: NewsBot Intelligence System 2.0

## 📌 Problem Statement
The **NewsBot Intelligence System 2.0** expands on the original midterm project by integrating **advanced NLP techniques** to enhance:
1. Sentiment analysis  
2. Bias detection  
3. Topic classification  
4. Named Entity Recognition (NER)  
5. Text summarization  
6. Multilingual support  

The goal was to create a **more robust and interactive system** for processing and analyzing news content.

---

## 🛠 Approach & Methodology

### **1. Data Collection & Preprocessing**
- Imported real and synthetic news articles.
- Cleaned text: lowercasing, removing punctuation, stopwords, and lemmatization.
- Tokenized data for further analysis.

### **2. Sentiment & Bias Detection**
- **VADER** and **TextBlob** for rule-based sentiment scoring.
- Bias detection based on subjectivity metrics and keyword analysis.

### **3. Advanced NLP Features**
- **Named Entity Recognition (NER)** using spaCy.
- **Text Summarization** using extractive methods.
- **Multilingual Support** with language detection and translation pipelines.

### **4. Topic Classification**
- TF-IDF vectorization combined with **Logistic Regression** and **Naive Bayes** classifiers.
- Categorized articles into predefined topics (politics, sports, technology, etc.).

### **5. User Interaction**
- Designed a conversational interface for querying sentiment, bias, topic, and summaries of articles.

---

## 📊 Results
- Improved sentiment classification accuracy over the midterm version.
- Successfully integrated **NER** to highlight key entities in articles.
- Provided **automated summaries** that preserved 80–90% of the original meaning.
- Expanded usability by supporting **multiple languages**.

---

## 🎯 Learning Outcomes
- Learned to extend an existing NLP pipeline with **advanced processing features**.
- Integrated **multiple models and tasks** into a single cohesive system.
- Enhanced skills in **project documentation, modular coding, and deployment preparation**.

---

## 📦 Requirements
```bash
pip install pandas numpy scikit-learn nltk spacy vaderSentiment textblob langdetect googletrans
python -m spacy download en_core_web_sm
