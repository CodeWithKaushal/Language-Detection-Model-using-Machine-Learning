# 🌍 Language Detection Model

A machine learning project that detects the language of input text with predictions across 17 languages. This project demonstrates the power of **Natural Language Processing (NLP)** and **Machine Learning** to classify languages efficiently using a trained **Naive Bayes** model and a user-friendly **Flask** web application.

## 🗣️ Supported Languages

1. English
2. Malayalam
3. Hindi
4. Tamil
5. Kannada
6. French
7. Spanish
8. Portuguese
9. Italian
10. Russian
11. Swedish
12. Dutch
13. Arabic
14. Turkish
15. German
16. Danish
17. Greek

---

## 📂 Features

- **Text Preprocessing**: Removes special characters, numbers, and other noise, and converts text to lowercase for better model accuracy.
- **Bag of Words (BoW)**: Converts text data into a numerical matrix for machine learning.
- **Modeling**: Uses **Multinomial Naive Bayes** for classification.
- **Web Interface**: Built with **Flask**, allowing users to input text and get real-time language predictions.
- **Deployment**: Hosted on **Render**, enabling easy access for testing and usage.

---

## 🚀 Try It Out!

👉 [Language Detection App](https://language-detection-model-using-machine.onrender.com/)

---

## 🛠️ How It Works

### 1. Data Preprocessing

- The text is cleaned to remove numbers, special characters, and other unwanted elements.
- All text is converted to lowercase.

### 2. Model Training

- **Bag of Words (BoW)** is used for feature extraction.
- The data is split into training and testing sets using `train_test_split`.
- The model is trained using **Multinomial Naive Bayes**, which is ideal for text classification tasks.

### 3. Web Application

- A Flask app accepts user input, preprocesses the text, and predicts the language using the trained model.
- Predictions are displayed in an easy-to-read format.

---

## 📦 Installation and Setup

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Flask
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
