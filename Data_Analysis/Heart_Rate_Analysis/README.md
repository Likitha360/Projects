# Heart_Rate_Analysis

#### A Python-based machine learning project to predict heart failure using clinical data, featuring data exploration, visualization, and model comparison.

## Description
This project aims to predict the likelihood of heart failure based on a dataset of clinical features such as age, cholesterol levels, and exercise-induced angina. It includes exploratory data analysis (EDA) to understand the dataset, visualizations to highlight key trends, and a comparison of two prediction approaches: a custom rule-based model and a Scikit-learn machine learning model (Logistic Regression). The dataset used is `heart.csv`, which contains 918 patient records with 12 features, including the target variable `HeartDisease` (0 = No, 1 = Yes).

- **Purpose**: Demonstrate data analysis and predictive modeling skills for healthcare applications, comparing a simple rule-based approach with a machine learning model.
- **Tech Stack**: Python, Pandas, Matplotlib, Plotly, Scikit-learn.
- **Status**: Functional as of March 2025, based on the provided dataset structure.

## Features
- **Data Exploration**: Summary statistics, missing value checks, and feature distribution analysis.
- **Visualization**: Bar charts for model accuracy and confusion matrices for performance evaluation.
- **Prediction Models**:
  - Rule-Based: A custom heuristic model 
  - Scikit-learn: A machine learning model 
- **Dataset**: 918 entries with features like `Age`, `Cholesterol`, `MaxHR`, and `HeartDisease`.

## Dataset Overview
- **Source**: `heart.csv` (from a public repository like Kaggle).
- **Columns**: 12 (e.g., `Age`, `Sex`, `ChestPainType`, `RestingBP`, `Cholesterol`, `HeartDisease`).
- **Size**: 918 rows, no missing values.
- **Target**: `HeartDisease` (binary: 0 = No heart disease, 1 = Heart disease).

## Prerequisites
- Python 3.x
- Required libraries: `pandas`, `matplotlib`, `plotly`, `scikit-learn`

## Output:
EDA: Console output with dataset info, statistics, and zero-value counts.
Visualizations: Bar chart comparing model accuracies and confusion matrices for both models.
Results: Accuracy scores and confusion matrices printed or plotted.

### Visualizations:
- Bar chart comparing accuracies (e.g., Rule-Based: 0.65, Scikit-learn: 0.85).
- Confusion matrices showing true positives, false negatives, etc., for both models.
