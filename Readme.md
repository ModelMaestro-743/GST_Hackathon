# GST Hackathon Model

This repository contains the code and report for the XGBoost classification model developed during the GST Hackathon. The project aims to classify GST data with high accuracy and recall using various machine learning techniques.

## Dataset

- **Size:** 785,133 rows and 22 columns (numerical and categorical).
- **Preprocessing:** Missing values in 5 columns were imputed using the median. Features were normalized using Min-Max scaling.

## Exploratory Data Analysis (EDA)

- **Correlation:** High correlation observed between some columns, indicating multicollinearity. Columns 3 and 4 had a strong correlation with the target.
- **Outliers:** Analyzed using descriptive statistics and visualizations.

## Model Development

- **Algorithms:** Logistic Regression, SVM, Random Forest, and XGBoost.
- **Final Model:** XGBoost was selected for its superior performance, with hyperparameter tuning done using GridSearchCV.

## Model Performance

- **XGBoost Results:**
  - Accuracy: 97.83%
  - Precision: 84.65%
  - Recall: 94.04%
  - F1-Score: 0.8910
  - ROC-AUC: 0.9948

## Libraries Used

- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Joblib


