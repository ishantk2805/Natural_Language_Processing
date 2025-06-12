# Sentiment Analysis using NLP and LSTM

## 📌 Project Overview
This repository demonstrates a full pipeline for sentiment analysis on movie reviews using Natural Language Processing (NLP) techniques and deep learning.

The project is split into two stages:
- **Notebook 1:** Exploratory data analysis and text preprocessing using classical NLP techniques.
- **Notebook 2:** Building and training an LSTM-based deep learning model using Keras to classify sentiment.

---

## 📖 Notebooks

### 🧹 01 - Natural Language Processing
Covers:
- Loading and inspecting the raw IMDb dataset
- Text preprocessing: lowercasing, punctuation removal, stopword filtering
- Tokenization and lemmatization
- Exploratory analysis on review lengths, word frequencies, and sentiment distribution

### 🤖 02 - LSTM Sentiment Analysis
Covers:
- Text vectorization and sequence padding
- Using an Embedding Layer to generate word vectors
- Designing and training an LSTM-based neural network
- Plotting training vs. validation accuracy/loss

---

## 🧠 Problem Statement
Can we train a model to correctly classify a movie review as positive or negative using only the text? This problem showcases the power of combining traditional NLP and modern deep learning.

---

## 📊 Dataset
IMDb Large Movie Review Dataset  
- 50,000 labeled movie reviews  
- Balanced classes  
- Pre-split into training and testing sets  

---

## 🧰 Tools & Libraries
- Python 3
- NLTK / re / string
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Sentiment_Analysis_NLP.git
   cd Sentiment_Analysis_NLP
