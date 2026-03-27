# Spam_mail_detection_ML
# 📧 Spam Mail Detection using Machine Learning

## 📌 Project Overview

This project focuses on building a machine learning model to classify emails as **Spam** or **Not Spam (Ham)**. It uses Natural Language Processing (NLP) techniques to analyze email text and identify patterns commonly found in spam messages.

---

## 🎯 Objective

* Detect spam emails with high accuracy
* Apply text preprocessing and NLP techniques
* Build and evaluate classification models
* Automate email filtering system

---

## 📂 Dataset

* Dataset used: **spam.csv**
* Features include:

  * `v1`: Label (Spam / Ham)
  * `v2`: Email text message

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy** – Data manipulation
* **Matplotlib, Seaborn** – Visualization
* **Scikit-learn** – ML models
* **NLTK / re (regex)** – Text preprocessing
* **Jupyter Notebook**

---

## 🔍 Project Workflow

### 1. Data Collection

* Loaded dataset from CSV file

### 2. Data Preprocessing

* Removed null values and duplicates
* Converted text to lowercase
* Removed punctuation and stopwords
* Tokenization and stemming

### 3. Feature Engineering

* Converted text into numerical format using:

  * CountVectorizer
  * TF-IDF Vectorizer

### 4. Model Building

* Naive Bayes (MultinomialNB)
* Logistic Regression
* Support Vector Machine (SVM)

### 5. Model Evaluation

* Accuracy Score
* Precision & Recall
* Confusion Matrix

---

## 📊 Results

* Naive Bayes achieved high accuracy for spam detection
* TF-IDF improved model performance
* Model effectively classifies unseen email messages

---

## 📈 Sample Prediction

* Input: “Congratulations! You won a free lottery ticket”

* Output: **Spam**

* Input: “Hey, are we meeting tomorrow?”

* Output: **Not Spam (Ham)**

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash id="clone1"
git clone https://github.com/your-username/spam-mail-detection.git
```

2. Navigate to the project folder:

```bash id="nav1"
cd spam-mail-detection
```

3. Install dependencies:

```bash id="install1"
pip install -r requirements.txt
```

4. Run the notebook:

```bash id="run1"
jupyter notebook
```

---

## 💡 Future Improvements

* Deploy using Flask / Streamlit web app
* Use Deep Learning (LSTM, BERT) for better accuracy
* Real-time email filtering integration
* Multi-language spam detection

---

## 👩‍💻 Author

**Priya B.G**

* 📧 [priyabg777@gmail.com](mailto:priyabg777@gmail.com)
* 🔗 GitHub: https://github.com/priya-naik6787
* 🔗 LinkedIn: https://www.linkedin.com/in/priya-b-g-935490245

---

## ⭐ Conclusion

This project demonstrates the application of **Natural Language Processing and Machine Learning** in solving a real-world problem. It showcases skills in **data preprocessing, feature engineering, and classification modeling**, making it suitable for entry-level **Data Analyst / Machine Learning roles**.

---
