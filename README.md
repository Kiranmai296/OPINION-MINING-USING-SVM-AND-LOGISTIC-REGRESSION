# Opinion Mining on Customer Reviews

## 📌 Project Overview

This project performs **Opinion Mining (Sentiment Analysis)** on customer online reviews using **Machine Learning models**. The goal is to classify customer feedback into **Positive, Negative, or Neutral** categories based on textual reviews.

### 🚀 Features

- **Data Preprocessing**: Cleaning, tokenization, and vectorization using **TF-IDF**.
- **Class Imbalance Handling**: Applied **SMOTE** and **class weight balancing**.
- **Machine Learning Models**:
  - **Support Vector Machine (SVM)** with **RBF Kernel**
  - **Logistic Regression**
  - **Voting Classifier** (Ensemble of SVM & Logistic Regression)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score.

---

## 📊 Dataset

- The dataset consists of customer reviews with sentiment labels (**Positive, Negative, Neutral**).
- Text reviews are preprocessed before feeding into models.

---

## 🛠 Model Implementation

### **1️⃣ Data Preprocessing**

- Removed stopwords, punctuation, and special characters.
- Applied **TF-IDF Vectorization** to convert text into numerical format.

### **2️⃣ Handling Imbalanced Data**

- Used **SMOTE (Synthetic Minority Over-sampling Technique)** to generate synthetic samples.
- Applied **class\_weight='balanced'** in models to adjust for class imbalance.

### **3️⃣ Model Training**

- **SVM (RBF Kernel)**: Used for non-linear decision boundary.
- **Logistic Regression**: Used for probabilistic classification.
- **Voting Classifier**: Combined predictions of SVM and Logistic Regression.

### **4️⃣ Model Evaluation**

- Used **Accuracy, Precision, Recall, and F1-score** to evaluate performance.
- Generated a classification report to analyze results.

---

## 📊 Results

| Model                    | Accuracy   |
| ------------------------ | ---------- |
| SVM (RBF)    +           |            |
| Logistic Regression      |            |
| with Voting Classifier   | **85.44%** |

---

## 🙌 Acknowledgments

- **Scikit-learn** for Machine Learning algorithms.
- **Imbalanced-learn (SMOTE)** for handling data imbalance.
- **NLTK & Pandas** for data preprocessing.

---

## 🏆 Author

👤 **Kiranmai Tirupati**

- GitHub: [@Kiranmai296](https://github.com/Kiranmai296)

