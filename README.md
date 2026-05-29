# Spam-Detection-Through-CSV-file
# 🛡️ SMS & Email Spam Detection System

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Pandas%20%26%20NumPy-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

An end-to-end Machine Learning pipeline that processes raw text data from custom CSV files to classify messages as **Ham (Legitimate)** or **Spam** with high precision. Built using Natural Language Processing (NLP) techniques and robust classification algorithms.

---

## 🚀 Key Features

* **Dynamic CSV Ingestion:** Seamlessly loads, cleans, and processes custom tabular text datasets.
* **Advanced NLP Pipeline:** Features comprehensive text preprocessing including tokenization, stop-word removal, and TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
* **High-Accuracy Classifiers:** Implements and compares top-tier algorithms like **Multinomial Naive Bayes (MNB)** and **Logistic Regression**.
* **Detailed Evaluation Analytics:** Generates confusion matrices, precision-recall metrics, and classification reports to thoroughly evaluate model performance.

---

## 🛠️ Tech Stack & Architecture

* **Language:** Python
* **Libraries:** `Pandas`, `NumPy`, `Scikit-Learn`
* **NLP Tools:** `CountVectorizer`, `TfidfTransformer` / `TfidfVectorizer`

### 🔄 The Pipeline Workflow
[ Raw CSV Input ] ➔ [ Data Cleaning & Label Encoding ] ➔ [ Text Vectorization (TF-IDF) ]
│
[ Model Deployment/Inference ] 🧱 ◀ [ Evaluation Metrics ] ◀ [ Model Training (Naive Bayes) ]

---

## 📊 Dataset Structure

The model expects a standardized `.csv` file format containing your text corpus. Ensure your data matches the following schema layout:

| label | text_content |
| :--- | :--- |
| `ham` | "Hey, are we still meeting for coffee this afternoon?" |
| `spam` | "WINNER! You have won a cash prize of $5000. Call 09061701461 to claim now!" |
| `ham` | "Can you send me the documentation file via email?" |

---

## ⚙️ Installation & Usage Guide

### 1. Clone the Repository
```bash
git clone [https://github.com/TheMaryamIsmail/Spam-Detection-System.git](https://github.com/TheMaryamIsmail/Spam-Detection-System.git)
cd Spam-Detection-System

pip install -r requirements.txt

python main.py

### 💡 Tips to maximize this README's impact:
1. **Update the URLs:** Make sure to replace `TheMaryamIsmail` with your exact repository path once you upload it so the "Let's Connect" and clone links work perfectly.
2. **Add a `requirements.txt` file:** Include a small file in your repository listing the tools you used, like this:
   ```text
   pandas==2.2.0
   numpy==1.26.0
   scikit-learn==1.4.0
