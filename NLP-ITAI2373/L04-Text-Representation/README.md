# L04 – Text Representation

## 📌 Problem Statement
The purpose of this lab was to explore different **text representation techniques** and understand how they affect **model performance** in Natural Language Processing (NLP) tasks.

---

## 🛠 Approach & Methodology
The following techniques were implemented and compared:

1. **Bag of Words (BoW)**  
   - Representing text as a set of word counts without considering order.

2. **Term Frequency–Inverse Document Frequency (TF-IDF)**  
   - Weighting words based on frequency in a document relative to the corpus.

3. **N-grams**  
   - Capturing sequences of words to preserve some contextual meaning.

4. **Word Embeddings** (Pre-trained models)  
   - Using dense vector representations that capture semantic relationships between words.

The comparison focused on **how these representations influence accuracy and computational efficiency** in downstream models.

---

## 📊 Results
- **BoW & TF-IDF** performed well on small datasets but lacked semantic understanding.  
- **N-grams** captured more context but increased dimensionality.  
- **Word Embeddings** (e.g., GloVe, Word2Vec) provided richer semantic features and improved model generalization.  

---

## 🎯 Learning Outcomes
- Gained hands-on experience with multiple feature extraction methods for NLP.  
- Understood trade-offs between **context capture** and **dimensionality**.  
- Learned how to choose the best representation method depending on the dataset and task.

---

## 📦 Requirements
```bash
pip install nltk scikit-learn gensim
