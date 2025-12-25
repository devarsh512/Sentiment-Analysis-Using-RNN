# 💬 Sentiment Analysis Using RNN

[![Great Learning Certificate](https://img.shields.io/badge/Great%20Learning-Project%20Certified-blue?style=for-the-badge&logo=google-scholar)](https://www.mygreatlearning.com/project-certificate/PC-A61B646C9C864F5D)

This project builds a **Recurrent Neural Network (RNN)** to classify tweet sentiments into
**positive, negative, neutral, and irrelevant** categories.

---

## 📌 Project Overview

Understanding sentiment in text data is crucial for applications such as social media monitoring,
customer feedback analysis, and opinion mining.  
This project uses deep learning techniques to analyze tweet sentiment.

---

## 🎯 Objectives

- Clean and preprocess tweet text
- Convert text into numerical representations
- Build an RNN-based deep learning model
- Train and evaluate the model using standard metrics

---

## 🧵 Dataset Description

- **Source:** Preprocessed Twitter dataset
- **Location:** `data/data.csv`
- **Classes:**
  - Positive
  - Negative
  - Neutral
  - Irrelevant

### Dataset Columns
- `tweet_id`
- `airline_sentiment`
- `text`

---

## 🧠 Model Architecture

- Embedding Layer
- Recurrent Neural Network (RNN)
- Dense Output Layer (Softmax)

**Loss:** Categorical Cross-Entropy  
**Optimizer:** Adam  

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- NLP Techniques

---

## 📜 Certificate

This project is supported by a verified **Great Learning Project Certificate**.

👉 [View Certificate](./certificates/Certificate.pdf)

---

## 🚀 Future Improvements

- Use LSTM or GRU for better performance
- Add word embeddings (GloVe)
- Improve text preprocessing

---

## 📜 License

Educational use only.
