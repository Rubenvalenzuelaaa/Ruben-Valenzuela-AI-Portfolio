# L07 – Sentiment & Emotion Analysis in the Real World

## 📌 Problem Statement
The goal of this lab was to perform **sentiment and emotion analysis** using both **text-based** and **audio-based** approaches.  
This included rule-based models, machine learning classifiers, and multimodal fusion to combine insights from text and speech.

---

## 🛠 Approach & Methodology

### **1. Text-Based Sentiment Analysis**
- **VADER** (Valence Aware Dictionary and sEntiment Reasoner)  
  - Used for short text sentiment classification (positive, neutral, negative).
- **TextBlob**  
  - Provided polarity and subjectivity scores.
- **Machine Learning Classifiers**  
  - TF-IDF vectorization + Naive Bayes / Logistic Regression.

### **2. Audio-Based Emotion Recognition**
- **Feature Extraction** with **Librosa**  
  - Extracted pitch, energy, MFCCs, and chroma features.
- **Emotion Classification**  
  - Used ML models to classify emotions such as happy, sad, angry, and neutral.

### **3. Multimodal Fusion**
- Combined text and audio predictions for more robust emotion detection.

---

## 📊 Results
- Text models achieved up to **85% accuracy** on sentiment classification.
- Audio models captured distinct patterns in pitch and energy, improving emotion recognition in spoken data.
- Multimodal fusion enhanced prediction reliability in noisy environments.

---

## 🎯 Learning Outcomes
- Learned how to integrate **rule-based** and **ML-based** sentiment analysis.
- Gained experience in **audio feature engineering** for emotion detection.
- Understood the benefits of **multimodal AI systems**.

---

## 📦 Requirements
```bash
pip install pandas numpy scikit-learn nltk spacy vaderSentiment textblob librosa
