# Fake News Detection using Machine Learning & NLP

This project is a machine learning-based system that detects whether a news article is real or fake using Natural Language Processing (NLP) techniques. The model is trained on labeled news data and learns patterns from text content to classify news accurately.

## 📌 Objective
To build a classifier that can automatically identify fake news articles and help reduce misinformation.

## ⚙️ Workflow
- Data preprocessing and cleaning (removing punctuation, links, stopwords, etc.)
- Combining title and text for better feature representation
- Converting text data into numerical features using TF-IDF Vectorization
- Training a machine learning model on labeled dataset
- Evaluating performance using accuracy and classification report
- Testing model on custom input news

## 🧠 Model Used
- TF-IDF Vectorizer  
- Logistic Regression / Passive Aggressive Classifier  

## 📊 Output
The model predicts whether a news article is:
- Real News  
- Fake News  

## 🛠️ Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Regex (re)

## 🚀 Result
The model achieves good accuracy in detecting fake news and can be further improved using deep learning models like LSTM or BERT.
