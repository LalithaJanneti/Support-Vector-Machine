# Support-Vector-Machine
SMS Spam Detection using Linear SVM This project uses Natural Language Processing (NLP) techniques to classify SMS messages as Spam or Ham (Not Spam). The dataset used is the SMS Spam Collection Dataset from Kaggle. 
# SMS Spam Detection using Linear SVM

## 📌 Project Overview
This project focuses on detecting **spam messages** using a **Linear Support Vector Machine (SVM)**. The dataset consists of SMS messages labeled as **ham (not spam)** or **spam**, and the goal is to classify them accurately.

I used **text preprocessing, feature extraction with TF-IDF, and Linear SVM for classification**. Additionally, I generated **WordClouds** to visualize the most frequent words in spam and ham messages.

---

## 📊 Dataset
- **Dataset Source:** [SMS Spam Collection Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Files Included:**
  - `spam.csv` – contains SMS messages and their labels (`ham` or `spam`).

### Dataset Columns:
- **label:** Message category (`ham` = non-spam, `spam` = spam).
- **message:** The actual text message.

---

## ⚙️ Functions & Workflow
### 1. **Data Preprocessing**
- Removed unnecessary columns.
- Converted labels (`ham`, `spam`) into binary format (0, 1).
- Cleaned text: lowercasing, removing punctuation, stopwords, and tokenizing.

### 2. **Feature Extraction**
- Used **TF-IDF (Term Frequency – Inverse Document Frequency)** to convert text into numerical feature vectors.

### 3. **Model Training**
- Implemented **Linear SVM (Support Vector Machine)** for classification.
- Chose Linear SVM because it works well with high-dimensional text data.

### 4. **Evaluation**
- Metrics used: **Accuracy, Precision, Recall, F1-score**
- Plotted confusion matrix for better understanding.

### 5. **WordCloud Visualization**
- Generated WordClouds to visualize frequent words in spam and ham messages.
- **WordCloud** is a visual representation of text data where the size of each word indicates its frequency or importance.
  - **Spam WordCloud** shows common words used in spam (e.g., "free", "win", "cash").
  - **Ham WordCloud** shows common words in normal messages.

---

## 📌 Results
- **Linear SVM achieved high accuracy** in classifying spam vs. ham.
- WordClouds helped identify important keywords that distinguish spam messages from normal ones.

