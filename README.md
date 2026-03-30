# Task-2-Sentiment-Analysis-using-NLP-Pipeline-ML-Models
# 📊 Sentiment Analysis using NLP & Machine Learning

## 👨‍💻 Author

**Abutalha Rahimoddin Parkote**
Internship: *Advanced Generative AI | February 2026*
Organisation: Innomatics Research Labs
Intern ID: IN226113802
Email: [abutalhaparkote@gmail.com](mailto:abutalhaparkote@gmail.com)

---

## 📌 Project Overview

This project implements a complete **Sentiment Analysis pipeline** using Natural Language Processing (NLP) and Machine Learning models. The system processes raw text reviews and classifies them as **Positive** or **Negative**.

The project follows an end-to-end workflow including preprocessing, feature extraction, model training, evaluation, and comparison.

---

## 📂 Dataset

* Source: Kaggle (IMDb Movie Reviews Dataset)
* Link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?utm_source=chatgpt.com
* Total Samples: ~50,000
* Features:

  * `review` → Text data
  * `sentiment` → Positive / Negative

---

## ⚙️ NLP Preprocessing

The following preprocessing steps were applied:

* Lowercasing text
* Removal of HTML tags
* Removal of punctuation and numbers
* Removal of stopwords *(while preserving negation words like "not")*
* Tokenization
* Lemmatization

Reusable preprocessing functions were implemented for clean and structured processing.

---

## Feature Engineering

Two techniques were used:

### 1. Bag of Words (BoW)

* Converts text into frequency-based vectors

### 2. TF-IDF

* Assigns importance to words based on frequency and uniqueness
* Also implemented with **n-grams (1,2)** for better context handling

---

## Machine Learning Models

The following models were trained and compared:

* Logistic Regression
* Naive Bayes
* Decision Tree

---

## Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

A comparison table and visualization were used to analyze performance.

---

## Results & Insights

* **Logistic Regression with TF-IDF performed best**
* TF-IDF outperformed Bag of Words due to better feature weighting
* Naive Bayes performed well and was computationally efficient
* Decision Tree showed lower accuracy due to overfitting

---

## Pipeline Flow

```
Raw Data 
→ Text Cleaning 
→ Tokenization & Lemmatization 
→ Feature Engineering (BoW, TF-IDF) 
→ Model Training 
→ Evaluation 
→ Comparison
```

---

## 📁 Project Structure

```
Sentiment-Analysis/
│── sentiment_analysis.ipynb
│── README.md
│── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository
2. Open the notebook in Jupyter/Colab
3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run all cells step-by-step

---

## Key Learnings

* Importance of NLP preprocessing in text classification
* Difference between BoW and TF-IDF
* Impact of feature engineering on model performance
* Model comparison and evaluation techniques

---

## 📌 Conclusion

This project demonstrates how raw textual data can be transformed into meaningful features and used effectively in Machine Learning models for sentiment classification.

---

## 🔗 Future Improvements

* Use advanced models like Random Forest or XGBoost
* Apply deep learning models (LSTM, BERT)
* Improve preprocessing using advanced NLP techniques

---
