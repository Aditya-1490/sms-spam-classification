# 📩 Email / SMS Spam Classifier

A machine learning–based Email/SMS spam detection system using Natural Language Processing (NLP) and deployed with Streamlit. The application classifies messages as **Spam** or **Not Spam** in real time.

---

## 🚀 Live Demo

https://sms-spamchecker.streamlit.app/

---

## 🧠 Project Overview

Spam messages are a common problem in digital communication. This project applies NLP techniques and a probabilistic machine learning model to accurately identify spam messages with high precision. The solution is lightweight, fast, and production-ready.

---

## 🛠 Tech Stack

- Python  
- scikit-learn  
- NLTK  
- pandas  
- NumPy  
- Streamlit  

---

## ⚙️ Methodology

- Text preprocessing (lowercasing, tokenization, stopword removal, stemming)
- Feature extraction using TF-IDF
- Classification using Multinomial Naive Bayes
- Model and vectorizer serialization using pickle
- Deployment using Streamlit Cloud

---

## 📊 Model Performance

- Model: Multinomial Naive Bayes  
- Precision (Spam class): **1.00**

---

## 📂 Project Structure
```text
sms-spam-classification/
│
├── app.py                   # Streamlit web application
├── main.py                  # Model training & preprocessing
├── model.pkl                # Trained spam classification model
├── vectorizer.pkl           # TF-IDF vectorizer
├── requirements.txt         # Project dependencies
├── .gitignore
└── README.md
```
## 🧪 Example

**Input:**
Congratulations! You have won ₹10,00,000 in our lucky draw. Claim now!

**Output**
Spam


