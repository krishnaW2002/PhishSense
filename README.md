# 🛡️ PhishSense - AI-Powered Email Phishing Detector

> Detect phishing emails using machine learning and natural language processing.

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-blue)
![ML Project](https://img.shields.io/badge/Project-Type%3A%20ML-lightgrey)

---

## 🚀 Overview

**PhishSense** is a smart AI model that analyzes the subject and content of emails to detect phishing attempts with high accuracy. It uses classic NLP techniques (TF-IDF) combined with Logistic Regression for real-time classification.

---

## 🧠 Features

- ✅ Real-time phishing email classification
- 🧾 Works on raw email text (subject + body)
- 🔍 TF-IDF vectorization for feature extraction
- 🤖 Machine Learning (Logistic Regression)
- 🧪 GUI & CLI versions included
- 🌐 Web version (Flask) — Coming soon!

---

## 📁 Dataset

This project uses a labeled dataset of email texts:


Sr. No	Email Text	Email Type
1	Your account is locked. Click here...	phishing email
2	Meeting notes attached. Please review.	safe email


---

## 🛠️ Installation

```bash
git clone https://github.com/krishnaW2002/phishsense.git
cd phishsense
pip install -r requirements.txt


📊 Model Performance
Accuracy: 94.2%

Precision: 95%

Recall: 92%

Confusion Matrix: ✅ included in notebook

🤖 Tech Stack
Python 3.10

Pandas, Scikit-learn, Numpy

Tkinter (for GUI)

Flask (for web)

TF-IDF Vectorizer

📌 To-Do
 Basic phishing classifier

 GUI Interface (Tkinter)

 Flask web interface 

 Upgrade to BERT-based model

 Deploy on HuggingFace or Streamlit

📄 License
MIT License © 2025 Krishna Wakode
