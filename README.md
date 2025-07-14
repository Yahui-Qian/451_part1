# 451_part1
WTI Oil Futures Direction Prediction

This repository contains the code and report for a machine learning project aimed at predicting the direction of daily returns for West Texas Intermediate (WTI) oil futures. The project uses lagged price features and XGBoost classification within a time series cross-validation framework.

Repository Structure

notebook/            → Jupyter notebook and HTML export
report/              → Final research report in PDF format
img/                 → ROC curves, confusion matrices, and other visual output
data/                → Input data (optional; may be downloaded separately)

# How to Run the Notebook

Clone this repository:

git clone https://github.com/Yahui-Qian/451_part1.git
cd 451_part1

Install the required libraries:

pip install -r requirements.txt

Open the notebook:

jupyter notebook notebook/451_pa1_jump_start_v001.ipynb

# Project Summary

The notebook demonstrates:

Feature engineering with lagged prices, HML, OMC, volume, and EMA

Target variable definition using log returns

Feature selection based on AIC and logistic regression

Classification using XGBoost with time series cross-validation

Model evaluation with accuracy, F1-score, AUC, and confusion matrix

Hyperparameter tuning with RandomizedSearchCV

# Report

Please refer to report/report.pdf for a complete summary of methodology, results, and interpretation.

# AI Assistance Disclosure

This project benefited from the use of AI assistance (OpenAI ChatGPT) for the following:

Drafting parts of the research report

Clarifying the use of AIC and time series validation

Structuring the README and directory organization

All analysis, code execution, and interpretation were done by the author.

