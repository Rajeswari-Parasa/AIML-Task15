# End-to-End ML Pipeline — Titanic Dataset

This project builds a complete Machine Learning Pipeline to predict passenger survival using the Titanic dataset. Preprocessing and model training are combined using Scikit-learn’s Pipeline and ColumnTransformer.

## Steps
- Load data and split features/target
- Preprocess numerical (impute + scale) and categorical (impute + encode) features
- Combine using ColumnTransformer
- Train Logistic Regression inside a Pipeline
- Evaluate with Accuracy, Precision, Recall, F1-score
- Save model as `.pkl`

## Files
- Titanic-Dataset.csv
- titanic_pipeline.ipynb
- titanic_pipeline_model.pkl

## Outcome

This project demonstrates how to build a robust ML pipeline used in real production systems, covering preprocessing, training, evaluation, and model saving.
