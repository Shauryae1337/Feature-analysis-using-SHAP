## Introduction

Phishing is a prevalent online threat, and this project aims to build and analyze a machine learning model for phishing detection. The primary tools used are the Random Forest algorithm for classification and SHAP for interpretability.

## Random Forest Model

The Random Forest model is trained on a dataset containing features related to URLs, including characteristics like length, presence of certain symbols, and domain information. The model is evaluated on a testing set, and its performance metrics are analyzed.

## SHAP Analysis

SHAP values are used to interpret the predictions of the Random Forest model. The SHAP summary plot is generated to visualize the impact of each feature on the model's output. Additionally, the mean absolute SHAP values are extracted and presented in tabular format.

## Files and Structure

- `notebook shapley.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and SHAP analysis.
- `dataset1.csv`: The dataset used for training and evaluation.
- `prediction values.xlsx`: Mean SHAP Values for each feature.
- `Images`: Graphs and Tables

    Python 3.x
    Jupyter Notebook
    Libraries: scikit-learn, shap, pandas, matplotlib

Install the required libraries using:

bash

pip install scikit-learn shap pandas matplotlib

Acknowledgments

    The dataset used in this project is sourced from 
    Special thanks to the open-source contributors of scikit-learn and SHAP for their valuable tools.
