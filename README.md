# Credit_Card_Fraud_detection

# Credit Card Fraud Detection 💳🚨

This project builds a machine learning pipeline to detect fraudulent credit card transactions using classification models such as Logistic Regression, Random Forest, and XGBoost. It includes data preprocessing, handling class imbalance, model tuning, evaluation, and visualization.

---

## 📁 Dataset

The dataset used is from [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains 284,807 transactions with 492 fraud cases (only ~0.17%).

**Note:** The dataset is not included in this repository to avoid exceeding GitHub’s file size limits.

---

## 📥 How to Get the Dataset

### 🔹 Option 1: Download Manually

1. Visit [Kaggle Dataset Page](https://www.kaggle.com/mlg-ulb/creditcardfraud)
2. Download `creditcard.csv`
3. Place the file in a `Data/` folder inside the project directory:


### 🔹 Option 2: Use Python Script (Requires Kaggle API)

If you have your Kaggle API credentials set up (`~/.kaggle/kaggle.json`), you can run:

```bash
python download_data.py


