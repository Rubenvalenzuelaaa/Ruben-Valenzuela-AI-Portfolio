# L02 – NLP Processing Techniques

## 📌 Problem Statement
The objective of this lab was to explore **fundamental Natural Language Processing (NLP) techniques** using Python libraries such as **NLTK** and **spaCy**.  
The tasks focused on preparing and processing raw text data for further NLP applications.

---

## 🛠 Approach & Methodology
The lab involved the following steps:

1. **Text Loading & Preprocessing**
   - Importing raw text data into Python.
   - Converting text to lowercase for normalization.

2. **Tokenization**
   - Splitting text into individual tokens (words or sentences) using NLTK and spaCy.

3. **Stopword Removal**
   - Removing common words (e.g., “and”, “the”) that do not add significant meaning.

4. **Lemmatization**
   - Reducing words to their base or dictionary form (e.g., "running" → "run").

5. **Part-of-Speech (POS) Tagging**
   - Assigning grammatical labels (noun, verb, adjective) to each token.

---

## 📊 Results
- Successfully implemented preprocessing steps that improve **text clarity** and **model efficiency**.
- Compared **NLTK** and **spaCy** performance, noting speed and tagging accuracy differences.
- Prepared clean datasets ready for feature extraction and further NLP tasks.

---

## 🎯 Learning Outcomes
- Learned how to **clean and normalize text data**.
- Gained experience in **POS tagging** with multiple NLP libraries.
- Understood the importance of preprocessing in **machine learning pipelines**.

---

## 📦 Requirements
```bash
pip install nltk spacy
python -m spacy download en_core_web_sm
