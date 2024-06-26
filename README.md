# Immuno-Oncology Applications of Genomic Data in Bladder Cancer

This project aims to utilize genomic data for immuno-oncology applications in bladder cancer. The analysis includes preprocessing of clinical and genomic data, feature selection, predictive modeling, and evaluation of model performance.

## Project Overview

1. **Data Preprocessing**: Load and preprocess clinical and genomic data, handle missing values, and encode categorical variables.
2. **Feature Selection**: Select the top features based on ANOVA F-value.
3. **Model Training and Evaluation**: Train an XGBoost model and evaluate its performance using accuracy, precision, recall, and confusion matrix.
4. **Visualization**: Visualize the confusion matrix and feature importances.

## Data

The data used in this project includes clinical data and genomic data. You can access the data from the following Google Drive link:

[Data Retrieval Link](https://drive.google.com/drive/folders/1Hz2B5ISJvUQBVTqVat1wYjuhuxwp1mTs?usp=sharing)

- **Clinical Data**: Contains patient demographics, treatment information, and cancer types.
- **Genomic Data**: Contains gene expression levels for various genes.

## Requirements

- Python 3.6 or above
- Jupyter Notebook
- Required Python libraries: pandas, numpy, sklearn, xgboost, matplotlib, seaborn, imbalanced-learn

