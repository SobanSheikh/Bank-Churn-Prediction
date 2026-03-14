# Bank Customer Churn Prediction

A production-grade machine learning project for predicting customer churn in a banking environment.

## Overview
This project utilizes XGBoost to identify customers at risk of leaving the bank. It features a complete pipeline from raw data acquisition to diagnostic evaluation and error analysis.

## Key Features
- **End-to-End Pipeline**: Transparent data cleaning and feature engineering.
- **Reproducibility**: Global seeding for deterministic model behavior.
- **Diagnostic Insights**: Quantitative and qualitative error analysis to identify high-risk boundary cases.
- **Engineering Hygiene**: Integrated unit testing for data integrity.

## Getting Started
1. Install dependencies: `pip install -r requirements.txt`
2. Run analysis: `notebooks/churn_analysis.ipynb`
3. Run tests: `python tests/test_pipeline.py`

## Project Report
Detailed technical insights can be found in the [Project Technical Report](project_technical_report.md).