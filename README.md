# Credit Card Fraud Detection with SMOTE 💳

### 📌 Project Overview
A Machine Learning system designed to detect fraudulent credit card transactions. The project tackles the challenge of **Class Imbalance** (0.17% fraud rate) using **SMOTE (Synthetic Minority Over-sampling Technique)** and a **Random Forest Classifier**.

### 📊 Key Results
* **Recall (Fraud Class):** 85% (Successfully caught 83/98 fraud cases in test set)
* **Precision (Fraud Class):** 91% (Very few false alarms)
* **Accuracy:** 99.9% (Note: Accuracy is not a valid metric for this dataset)

![Confusion Matrix](images/confusion_matrix.png)

### 🛠️ Tech Stack
* **Python:** Pandas, NumPy
* **ML Libraries:** Scikit-Learn, Imbalanced-Learn
* **Techniques:** SMOTE, Random Forest, Robust Scaling

### 🚀 How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place creditcard.csv in the root folder.
4. Run the notebook credit_card_fraud.ipynb

