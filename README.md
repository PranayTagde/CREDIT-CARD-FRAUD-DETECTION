# 💳 Credit Card Fraud Detection

This project implements a machine learning-based solution to detect fraudulent transactions using the famous Credit Card Fraud Detection dataset. It leverages supervised learning algorithms, data preprocessing, and visualization techniques to accurately classify legitimate and fraudulent transactions.

## 📊 Dataset

The dataset contains transactions made by European cardholders in September 2013. It presents transactions that occurred in two days, with 492 frauds out of 284,807 transactions.

> **Note:** Due to confidentiality, features V1 to V28 are the result of a PCA transformation. Only `Time`, `Amount`, and `Class` are available in plain form.

## 🚀 Project Workflow

- Importing and inspecting the dataset
- Handling class imbalance using undersampling
- Data visualization using Seaborn and Matplotlib
- Feature scaling using StandardScaler
- Model training using:
  - Logistic Regression
  - Random Forest Classifier
- Model evaluation with:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
  - ROC-AUC Curve

## 🧪 How to Run

1. Install the required dependencies:

```bash
pip install -r requirements.txt
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook CREDIT CARD FRAUD DETECTION.ipynb
```
3. Execute each cell step-by-step to perform preprocessing, training, and evaluation.


## 📦 Requirements

All dependencies are listed in the `requirements.txt` file. Key libraries include:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `imbalanced-learn`


## 📁 Project Structure

```bash
📂 Credit-Card-Fraud-Detection
├── CREDIT CARD FRAUD DETECTION.ipynb # Main Jupyter Notebook
├── requirements.txt # Required Python libraries
└── README.md # Project documentation
```

## 📚 Reference
- [Kaggle Dataset – Credit Card Fraud Detection](https://www.kaggle.com/datasets/kartik2112/fraud-detection)