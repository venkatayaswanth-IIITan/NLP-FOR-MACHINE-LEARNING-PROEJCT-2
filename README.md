# 📧 SMS Spam Classification using NLP and TF-IDF

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Naive%20Bayes-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🚀 Project Overview

This project implements an **SMS Spam Detection System** using **Natural Language Processing (NLP)** and **TF-IDF (Term Frequency–Inverse Document Frequency)**.

The model automatically classifies SMS messages into:

* 📧 **Spam** → Unwanted promotional or fraudulent messages
* ✅ **Ham** → Genuine and legitimate messages

The project uses text preprocessing techniques, TF-IDF vectorization, and a **Multinomial Naive Bayes** classifier to achieve high prediction accuracy.

---

## 🎯 Objective

The main objective of this project is to:

* Detect spam messages automatically.
* Reduce unwanted SMS communications.
* Apply NLP techniques to real-world text classification problems.
* Build an efficient machine learning model for spam detection.

---

## 🛠️ Technologies Used

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📚 NLTK
* 🤖 Scikit-Learn
* 📝 NLP
* 📈 TF-IDF Vectorization
* 🎯 Multinomial Naive Bayes

---

## 📂 Dataset

The project uses the **SMS Spam Collection Dataset**.

### Dataset Structure

| Column | Description      |
| ------ | ---------------- |
| v1     | Label (spam/ham) |
| v2     | SMS Message      |

### Example

| Label | Message                          |
| ----- | -------------------------------- |
| spam  | Congratulations! You won ₹10,000 |
| ham   | Are you coming to class today?   |

---

# 🔄 Project Workflow

```text
SMS Dataset
      ↓
Text Preprocessing
      ↓
Tokenization
      ↓
Stopword Removal
      ↓
Stemming
      ↓
TF-IDF Vectorization
      ↓
Feature Matrix
      ↓
Train-Test Split
      ↓
Multinomial Naive Bayes
      ↓
Spam/Ham Prediction
      ↓
Model Evaluation
```

---

# 🧠 NLP Preprocessing Steps

## 1️⃣ Text Cleaning

Removes:

* Special Characters
* Punctuation
* Numbers

### Example

Before:

```text
Congratulations!!! You won ₹5000
```

After:

```text
Congratulations You won
```

---

## 2️⃣ Lowercase Conversion

Converts all text into lowercase.

```text
FREE PRIZE
```

↓

```text
free prize
```

---

## 3️⃣ Tokenization

Breaks text into individual words.

```text
I Love NLP
```

↓

```python
['I', 'Love', 'NLP']
```

---

## 4️⃣ Stopword Removal

Removes common words:

```text
is
the
and
a
an
```

---

## 5️⃣ Stemming

Converts words to root form.

```text
running → run
playing → play
studies → studi
```

---

# 📊 TF-IDF Vectorization

TF-IDF stands for:

> **Term Frequency – Inverse Document Frequency**

TF-IDF converts text into numerical vectors while considering both:

* Word Frequency
* Word Importance

### Formula

```text
TF-IDF = TF × IDF
```

### Benefits

✅ Better than Bag of Words

✅ Gives importance to meaningful words

✅ Reduces impact of common words

✅ Improves model performance

---

# 🤖 Machine Learning Model

## Multinomial Naive Bayes

The project uses the **Multinomial Naive Bayes Classifier**.

### Why Naive Bayes?

* Fast Training
* Efficient Prediction
* Excellent for Text Classification
* Works well with TF-IDF Features

---

# 📈 Model Evaluation

The model performance is evaluated using:

---

## Accuracy Score

Measures overall correctness.

```text
Accuracy =
Correct Predictions
------------------
Total Predictions
```

---

## Classification Report

Provides:

* Precision
* Recall
* F1-Score

---

## Confusion Matrix

Shows:

| Actual         | Predicted             |
| -------------- | --------------------- |
| True Positive  | Correct Spam          |
| True Negative  | Correct Ham           |
| False Positive | Ham predicted as Spam |
| False Negative | Spam predicted as Ham |

---

# 📧 Example Predictions

### Input

```text
Congratulations! You won a free iPhone.
```

### Output

```text
📧 SPAM
```

---

### Input

```text
Are you attending NLP class today?
```

### Output

```text
✅ HAM
```

---

# 🌟 Applications

* 📧 Email Spam Detection
* 📱 SMS Spam Filtering
* 💳 Fraud Message Detection
* 🏦 Banking Security Systems
* 🌐 Social Media Monitoring
* 🔐 Cyber Security Applications

---

# 📁 Project Structure

```text
SMS-Spam-Classifier-TFIDF/
│
├── spam.csv
├── spam_classifier.py
├── README.md
├── requirements.txt
│
└── outputs/
     ├── accuracy_score
     ├── classification_report
     └── confusion_matrix
```

---

# ▶️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/SMS-Spam-Classifier-TFIDF.git
```

## Install Dependencies

```bash
pip install pandas numpy nltk scikit-learn
```

---

# ▶️ Run Project

```bash
python spam_classifier.py
```

---

# 🎓 Learning Outcomes

This project helped in understanding:

* Natural Language Processing (NLP)
* Text Preprocessing
* Tokenization
* Stopword Removal
* Stemming
* TF-IDF Vectorization
* Machine Learning
* Naive Bayes Classification
* Model Evaluation Metrics

---

# 📌 Future Enhancements

* Use Word2Vec Embeddings
* Use BERT Models
* Deploy as Web Application
* Real-Time SMS Filtering
* Deep Learning Based Classification

---

# 👨‍💻 Author

### Chatakondu Venkata Yaswanth

**B.Tech CSE | IIIT Kottayam**

### Skills Demonstrated

* Python
* NLP
* Machine Learning
* TF-IDF
* Scikit-Learn
* Data Preprocessing
* Text Classification

---

## ⭐ Resume Description

> Developed an SMS Spam Classification System using Natural Language Processing (NLP), TF-IDF Vectorization, and Multinomial Naive Bayes. Implemented text preprocessing techniques including tokenization, stopword removal, and stemming to classify messages as Spam or Ham with high accuracy. Evaluated performance using Accuracy Score, Classification Report, and Confusion Matrix. 🚀💯

---

### 🌟 If you found this project useful, give it a star on GitHub! ⭐
