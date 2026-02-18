# spam-comment-detection


Here’s a **short and clean GitHub description** for your complete project:

---

# 🚫 Spam Comment Detection Web App

A simple **Flask-based web application** that detects spam comments from uploaded CSV files using **Machine Learning (TF-IDF + Naive Bayes)**.

## 🔍 Overview

This project allows users to upload a CSV file containing comments. The system automatically:

* Detects the comment column
* Processes text using TF-IDF vectorization
* Classifies comments as:

  * **Spam 🚫**
  * **Not Spam ✅**
* Displays prediction results in a table (first 50 rows)

## 🛠️ Tech Stack

* Python
* Flask
* Pandas
* Scikit-learn
* HTML + CSS

## 🚀 Features

* CSV upload support
* Automatic comment column detection
* Encoding error handling (UTF-8 / Latin1)
* Empty file validation
* Clean and minimal UI
* Real-time prediction display

## ▶️ How to Run

```bash
pip install -r requirements.txt
python app.py
```

Open in browser:

```
http://127.0.0.1:5000/
```

---

A lightweight and beginner-friendly AI project demonstrating how Machine Learning can be integrated into a real web application.

⭐ Star the repo if you find it useful!
