End-to-End Machine Learning Pipeline — Titanic Dataset
Project Overview

This project demonstrates a complete End-to-End Machine Learning Pipeline using the Titanic dataset to predict whether a passenger survived or not. The workflow follows real-world ML practices by combining data preprocessing and model training into a single Scikit-learn Pipeline.

Tools & Libraries

Python

Pandas, NumPy

Scikit-learn (Pipeline, ColumnTransformer)

Jupyter Notebook / Google Colab

Pickle

Dataset

Titanic Dataset (CSV)

Target Variable: Survived

Workflow

Load dataset and split features & target

Identify numerical and categorical columns

Create preprocessing pipelines:

Numerical: Missing value imputation + Scaling

Categorical: Missing value imputation + OneHotEncoding

Combine preprocessing using ColumnTransformer

Build a full Pipeline with preprocessing + Logistic Regression

Split data into train and test sets

Train the pipeline and generate predictions

Evaluate using Accuracy, Precision, Recall, and F1-score

Save the trained pipeline as a .pkl file

Why Pipeline?

Prevents data leakage

Ensures consistent preprocessing during training and testing

Clean, reusable, and production-ready approach

Evaluation Metrics

Accuracy

Precision

Recall

F1 Score

Saved Model

titanic_pipeline_model.pkl — can be loaded later for direct predictions without retraining.

Project Structure
Task15_ML_Pipeline/
├── Titanic-Dataset.csv
├── titanic_pipeline.ipynb
├── titanic_pipeline_model.pkl
└── README.md

Outcome

This project demonstrates how to build a robust ML pipeline used in real production systems, covering preprocessing, training, evaluation, and model saving.
