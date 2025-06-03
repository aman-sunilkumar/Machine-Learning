# 📉 Telecom Customer Churn Prediction

This project analyzes telecom customer behavior to predict churn using various machine learning models. The goal is to enable targeted retention strategies and reduce customer attrition.

## 🎯 Objective

To identify key drivers of churn and build predictive models that accurately classify whether a customer is likely to churn. This supports business decision-making around customer engagement and retention.

## 📁 Project Structure

- `Telecom-churn.ipynb`: Main notebook with full end-to-end workflow — data cleaning, EDA, feature engineering, model training, and evaluation.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: Input dataset sourced from IBM’s open datasets on Kaggle.
- `Customer Churn Prediction.pdf`: Presentation slide deck explaining the business case, methodology, and outputs.

## 🧪 Methodology

### 🔍 Data Analysis
- **Initial Analysis**: Checking nulls, data types, basic distributions
- **Graphical Analysis**: KDE plots, categorical count plots, target distribution, feature importance
- **Data Cleaning**: Type conversions, removing/handling missing values

### 🛠 Feature Engineering
- Converting `SeniorCitizen` to categorical
- Encoding categorical variables
- Dropping irrelevant features (`customerID`)

### 🤖 Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### 📊 Model Evaluation
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score

## 📌 Key Insights

- Customers with month-to-month contracts and high monthly charges are more likely to churn.
- Long-tenure customers on yearly contracts with paperless billing show higher retention.
- Logistic Regression and Random Forest provided the best balance of performance and interpretability.

## 💼 Business Impact

With accurate churn prediction:
- Telecom providers can reduce churn through proactive outreach
- Marketing budgets can be optimized to target high-risk segments
- Customer satisfaction and lifetime value can be significantly improved

## 🚀 How to Run

1. Clone this repo.
2. Install dependencies (e.g., `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`)
3. Open `Telecom-churn.ipynb` in Jupyter and run all cells.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
