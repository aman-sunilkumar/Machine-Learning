# 🧠 Customer Segmentation for Loan Offer Conversion

This project focuses on identifying customer segments with a high likelihood of conversion for loan offers, using a combination of exploratory data analysis, feature engineering, and classification modeling techniques.

## 📌 Objective

To develop a data-driven strategy to segment customers and prioritize those most likely to convert on loan offers. This allows for targeted marketing, optimized resource allocation, and improved ROI.

## 🗂️ Project Structure

- `cust_seg_web1.ipynb`: Main analysis notebook containing all data preprocessing, EDA, feature engineering, model building, and evaluation steps.
- `test.csv`: Dataset used for training and testing classification models.
- `Customer Segmentation – Case Study.pptx`: Supporting slide deck explaining the approach and methodology.

## 🧰 Key Techniques Used

- **Exploratory Data Analysis (EDA)**:
  - Univariate and Bivariate Analysis
  - Handling missing values using central tendency and class mean substitution
  - Detection and treatment of outliers

- **Feature Engineering**:
  - Creation of derived variables to uncover hidden patterns
  - Weight of Evidence (WOE) encoding
  - Interaction terms and variable binning

- **Modeling Approaches**:
  - Logistic Regression with linearized features
  - Tree-based models (e.g., Decision Trees) to capture non-linear patterns and interactions

- **Performance Evaluation**:
  - Confusion Matrix
  - Accuracy, Precision, Recall, and F1 Score

## 💡 Insights

- Identification of statistically significant predictors
- Formation of interpretable rules through tree-based models
- Segments with high predicted probability of conversion were clearly defined and visualized

## 📈 Outcome

A data-backed approach to loan marketing strategies, enabling smarter targeting and campaign execution. The model allows for dynamic segment definition based on conversion likelihood.

## 📁 How to Run

1. Clone this repository.
2. Install dependencies (if any listed in `requirements.txt`).
3. Open and run `cust_seg_web1.ipynb` in Jupyter Notebook or your preferred IDE.
