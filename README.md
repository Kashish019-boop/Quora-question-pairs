# QuoraTwin

An NLP project to detect whether two given questions are semantically the same or not, inspired by the [Kaggle Quora Question Pairs Dataset](https://www.kaggle.com/c/quora-question-pairs).

## 📌 Project Overview
QuoraTwin is designed to tackle the problem of duplicate questions by leveraging Natural Language Processing (NLP) techniques. The project focuses on feature engineering and machine learning models to classify whether a pair of questions are duplicates (semantically similar) or not.

## 📊 Dataset
- Source: [Quora Question Pairs - Kaggle](https://www.kaggle.com/c/quora-question-pairs)
- Contains over 400,000 labeled question pairs.

## ⚙️ Features
- Text preprocessing (tokenization, stopword removal, lemmatization).  
- Feature extraction using Bag-of-Words and handcrafted features.  
- Applied multiple ML models for classification (Logistic Regression, Naive Bayes, etc.).  
- Evaluated models using accuracy, precision, recall, and F1-score.

## 🛠️ Tools & Technologies
- **Python**  
- **Scikit-learn, NLTK, Pandas, NumPy, Matplotlib**  
- **Jupyter Notebook**  

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Kashish019-boop/QuoraTwin.git

2. Install dependencies:
   ```bash
    pip install -r requirements.txt

3. Open Jupyter Notebook and run the project:
   ```bash
   jupyter notebook
