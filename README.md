# 💬 Persian Sentiment Analysis – Food Delivery Comments

This project performs sentiment classification on Persian-language food delivery reviews using a mix of rule-based labeling and supervised learning.
 
> 🏆 Achieved **97.7% F1-score** and **0.976 AUC** using Logistic Regression

---

## 📌 Overview

- Preprocessed and normalized over **56,000 Persian comments**.
- Removed unwanted characters, symbols, and stopwords.
- Used the **PerSent1 sentiment lexicon** to calculate polarity scores and auto-label comments.
- Balanced the dataset using undersampling.
- Trained a **Logistic Regression classifier** on vectorized text (via `CountVectorizer`).
- Evaluated with **confusion matrix**, **F1-score**, and **AUC**.

---

## 🧰 Tech Stack

- Python
- Pandas & NumPy
- scikit-learn
- imbalanced-learn
- CountVectorizer
- Regex for text cleaning



## 📁 Project Structure

