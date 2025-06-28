# confpaper

This repository contains the Python code and experimental workflow for a research project comparing traditional manual data cleaning and modeling methods with AI-driven automated machine learning (AutoML) approaches across three real-world datasets from different sectors: healthcare, environmental monitoring, and retail.

Project Overview
The study aims to:

Evaluate how AI-based workflows improve predictive performance and reduce manual effort.

Apply and compare models on datasets with varied challenges, including class imbalance, missing data, and high dimensionality.

Provide empirical evidence to support integrating AI into data quality management processes.

Contents
The repository includes three main Python scripts:

healthcare_diabetes_prediction.py – Classification of diabetes status using manual preprocessing and AI-based PyCaret workflows.

environmental_aqi_prediction.py – Regression task predicting Air Quality Index (AQI) from pollution metrics, comparing manual linear regression with automated model selection.

retail_sales_forecasting.py – Regression task forecasting total weekly sales, comparing traditional normalization and linear models with AI-driven regularization and ensemble techniques.

Each script follows a consistent structure:

Data loading and exploration.

Manual data cleaning (imputation, normalization, deduplication).

Manual baseline model training.

AI-based preprocessing and automated model comparison using PyCaret.

Performance evaluation and comparison.

Key Findings
AI-driven workflows significantly reduced mean absolute error (MAE) and improved macro F1 scores and R² across datasets.

Automated pipelines handled missing values and class imbalance more effectively.

Best model selection reflected data complexity: e.g., LightGBM for imbalanced healthcare data, K Neighbors Regressor for non-linear AQI prediction, and Ridge Regression for retail data with multicollinearity.

Why this matters
The project demonstrates the practical value of AutoML tools like PyCaret in real-world data science workflows, showing how they complement domain knowledge to deliver robust, reproducible, and scalable models.
