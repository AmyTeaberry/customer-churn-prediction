# customer-churn-prediction
Predicting customer churn using Logistic Regression and Random Forest with sklearn

## Project Overview

Customer churn — when a user stops using a service — is one of the most
costly problems in subscription-based businesses. This project builds and
evaluates predictive models to identify at-risk customers before they leave,
using real-world telecom data.

**Key Questions Answered:**
- Which customers are most likely to churn?
- What factors drive churn the most?
- Which model performs better: Logistic Regression or Random Forest?

## Dataset

**Source:** [Telco Customer Churn – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

7,043 customers × 21 features, including contract type, monthly charges,
tenure, and customer service interactions. Target variable: `Churn` (Yes/No).

## Methods

- Exploratory Data Analysis (EDA)
- Data cleaning and feature engineering
- Label encoding and one-hot encoding for categorical variables
- Logistic Regression (baseline model)
- Random Forest Classifier (ensemble model)
- Model evaluation: Accuracy, Precision, Recall, F1, ROC-AUC
- Feature importance analysis

## Tools & Libraries

- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

## Project Structure

customer-churn-prediction/
│
├── data/                    # Raw dataset (not tracked by git)
├── notebooks/
│   └── churn_prediction.ipynb   # Main analysis notebook
├── README.md
├── requirements.txt
└── .gitignore

## Results

*(To be updated after modeling is complete)*

## Background & Motivation

Having executed retention-focused marketing campaigns professionally,
I built this project to understand the statistical and algorithmic foundations
of churn prediction — moving from campaign execution to building models that
identify at-risk customers before intervention is needed.

## Author

**Jinhui (Amy) Tang**
NYU Steinhardt, BS Media, Communication & Culture | Minor: Computer Science
