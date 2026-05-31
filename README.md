# Fraud Detection System

A machine learning pipeline for detecting fraudulent transactions, accompanied by an interactive Streamlit web application for real-time model demonstration.

## Overview

This project develops and deploys a machine learning model to identify fraudulent transactions. The solution includes a complete end-to-end pipeline—from data preprocessing and feature engineering to model training and evaluation—along with a user-friendly Streamlit interface that allows users to test the model with random or custom input values.

## Project Workflow

- Imported required Python packages and libraries.
- Performed data preprocessing, including cleaning, handling missing values, and encoding categorical features.
- Conducted exploratory data analysis and generated visualizations using multiple chart types.
- Applied feature engineering techniques to improve model performance.
- Selected, trained, and evaluated a machine learning model.
- Exported the trained pipeline for reproducibility.
- Built and deployed a Streamlit web application to demonstrate model predictions on unseen data.

## Results & Impact

- Designed and trained a machine learning model capable of detecting fraudulent transactions.
- Achieved **94% accuracy** on the test set.
- Delivered an interactive Streamlit application that enables stakeholders to evaluate model behavior with arbitrary input values.

## Technologies & Tools

- **Programming Language**: Python
- **Development Environment**: Jupyter Notebook
- **Core Libraries**:
  - scikit-learn (for model training, preprocessing, and evaluation)
  - Matplotlib (for data visualization)

## Techniques & Skills Demonstrated

- Logistic Regression classifier
- Data preprocessing with `StandardScaler` and `OneHotEncoder`
- Pipeline construction for end-to-end reproducibility
- Train-test split for model validation
- Confusion matrix and classification report for performance evaluation

## How to Run

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

## Run in the terminal
Launch the Streamlit app:

streamlit run app.py
