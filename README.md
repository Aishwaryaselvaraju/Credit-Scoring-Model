# Credit Scoring Model

This project builds a credit scoring model to predict whether a customer will default on their loan based on their financial history. The dataset used contains customer features such as age, income, job type, and credit history.

## Dataset

- Dataset: `credit_data.csv` (Replace with your own dataset or provide a link)
- This dataset includes columns like: `age`, `job_type`, `income`, `credit_history`, and `target`.

## Steps:

1. **Data Preprocessing**: Cleaned missing values, scaled numerical features, and encoded categorical variables.
2. **Model Building**: Built three classification models:
    - Logistic Regression
    - Decision Tree Classifier
    - Support Vector Machine (SVM)
3. **Model Evaluation**: Evaluated models using metrics like:
    - Classification Report
    - AUC-ROC Score
    - Confusion Matrix (for Logistic Regression)

## Requirements:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `joblib`

Install dependencies with:

## Model Saving:

The Logistic Regression model is saved as `logistic_regression_model.pkl` for future use.


