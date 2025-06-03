# 💳 Credit Scoring Model – Lending Club

This project builds a credit scoring model to evaluate the likelihood of loan default for borrowers on the Lending Club platform. Using historical loan performance data and borrower attributes, we apply machine learning techniques to classify risk and support data-driven lending decisions.

## 🎯 Objective

To predict loan default (credit risk) using Lending Club’s dataset by:
- Engineering meaningful features from raw data
- Identifying key indicators of creditworthiness
- Applying classification models to assess risk
- Enabling better decision-making in peer-to-peer lending platforms

## 📁 Project Structure

- `Credit Scoring Lending Club.ipynb`: End-to-end notebook covering data prep, EDA, modeling, and evaluation.
- `LCDataDictionary.xlsx`: Official Lending Club Data Dictionary describing feature definitions.
- `README.md`: Project documentation.

## 🧪 Methodology

### 🔍 Data Exploration & Cleaning
- Loaded Lending Club loan data
- Reviewed schema using `LCDataDictionary.xlsx`
- Cleaned missing values and irrelevant features
- Standardized numerical and categorical formats

### 🧠 Feature Engineering
- Converted string and date fields into structured formats
- Derived new features from loan, income, and credit history variables
- One-hot encoded categorical features

### 🤖 Model Development
- **Target Variable**: Loan status – good (fully paid) vs. bad (default, charged off, etc.)
- **Classification Models Used**:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest
  - Gradient Boosting

### 📊 Evaluation Metrics
- Accuracy
- Precision / Recall
- F1-Score
- ROC-AUC Curve
- Confusion Matrix

## 🔍 Key Insights

- Features such as **loan amount**, **annual income**, **debt-to-income ratio**, and **loan grade** had high predictive power.
- Models like **Gradient Boosting** and **Random Forest** outperformed simpler classifiers.
- Imbalanced class handling was essential due to skewed distribution of defaults vs. fully paid loans.

## 💼 Business Impact

This project demonstrates how credit scoring models can:
- Reduce risk exposure for lenders
- Improve default prediction accuracy
- Streamline automated loan approval pipelines
- Support fairer and data-driven lending practices

## 🚀 How to Run

1. Clone the repo.
2. Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
