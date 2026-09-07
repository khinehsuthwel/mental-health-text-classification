# Mental Health Classification from Social Media Text

## Project Overview

This project compares different feature representation techniques and machine learning models for classifying social media text into seven mental health-related categories: Anxiety, Bipolar, Depression, Normal, Personality Disorder, Stress, and Suicidal.
The project evaluates five approaches:

- TF-IDF + Logistic Regression
- TF-IDF + SVM
- Word2Vec + Logistic Regression
- Word2Vec + SVM
- BERT

LIME is additionally used to provide interpretations for individual model predictions.

## How to Run

The project is implemented using Python notebooks and can be run using Google Colab or Jupyter Notebook.
- Open the required .ipynb file.
- Upload or replace the path of the required dataset.
- Run the notebook cells.

The repository contains five notebooks, with each notebook corresponding to one of the classification pipelines.

## Dataset

Two datasets from Kaggle were used:

- Dataset 1 – Sentiment & Mental Health Dataset (Reddit-Based): Used as the primary dataset for model development and evaluation. [1] 
- Dataset 2 – Mental Health: Used as an independent dataset to evaluate model generalisation. [2]

### References
[1] Kareem, M. (2026) ‘Sentiment & Mental Health Dataset (Reddit-Based)’. Kaggle. Available at: https://doi.org/10.34740/KAGGLE/DS/9330738.

[2] LIM, S.G. (2025). Depression detection using sentiment analysis. Kaggle. Available at: https://www.kaggle.com/datasets/szegeelim/mental-health


