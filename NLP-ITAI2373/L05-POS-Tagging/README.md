# L05 – Part-of-Speech Tagging in the Real World

## 📌 Problem Statement
The purpose of this lab was to apply **Part-of-Speech (POS) tagging** techniques to real-world text datasets, evaluating different NLP pipelines and their performance.  
POS tagging is an essential step in many NLP tasks, such as **sentiment analysis**, **chatbot development**, and **information extraction**.

---

## 🛠 Approach & Methodology
The lab involved the following steps:

1. **Preprocessing Messy Text**
   - Cleaning and normalizing raw datasets (removing extra spaces, special characters, etc.).

2. **POS Tagging Implementation**
   - Using **NLTK** and **spaCy** to assign grammatical categories to tokens.

3. **Case Study: Customer Service Transcripts**
   - Applying POS tagging to identify nouns, verbs, and adjectives relevant for customer sentiment.

4. **Benchmarking Model Performance**
   - Comparing tagging accuracy and speed between libraries.

---

## 📊 Results
- **spaCy** demonstrated faster execution and more consistent tagging on longer sentences.
- **NLTK** provided flexibility for rule-based modifications but was slower for large datasets.
- POS tagging significantly improved the **accuracy of sentiment classification** when combined with other NLP techniques.

---

## 🎯 Learning Outcomes
- Learned how to integrate POS tagging into **real-world NLP pipelines**.
- Understood performance trade-offs between different NLP libraries.
- Recognized the importance of grammatical structure in **downstream tasks** like chatbots and sentiment analysis.

---

## 📦 Requirements
```bash
pip install nltk spacy
python -m spacy download en_core_web_sm
