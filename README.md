
# What Factors Determine Income? (Adult Census Dataset)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-yellow)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-red)
![Optuna](https://img.shields.io/badge/Tuning-Optuna-blueviolet)

School project realized by Bonifas Olivier, Filloux Louis, and Gendronneau Maël.

## Project Description

The primary objective of this project is to analyze the "Adult" Census dataset (from the 1994 UCI Machine Learning Repository) to identify key factors associated with income levels.

We developed binary classification models to predict whether an individual earns more or less than $50,000 per year. The project emphasizes handling an imbalanced dataset and optimizing hyperparameters.

[View Project Presentation (Google Slides)](https://docs.google.com/presentation/d/1U9sC-fVjrsW1mPk_5qYdJBMDkNg3EcZfit-crIOP9YY/edit?usp=sharing)

## Repository Content

* **Adult_Income.ipynb**: The main notebook containing the entire code (EDA, Feature Engineering, Modeling, Stacking).
* **adult.csv**: The raw dataset used for the analysis.
* **profile.html**: Detailed exploratory analysis report (generated via YData Profiling).
* **requirements.txt**: List of necessary dependencies.

## Technologies and Methodology

The project follows a complete Data Science pipeline using advanced libraries:

1. Exploratory Data Analysis (EDA)
Usage of Pandas and YData Profiling (profile.html) as well as interactive visualizations with Plotly.

2. Modeling (Machine Learning)
We tested and compared several algorithms, including advanced boosting methods:
* Base Models: Logistic Regression, Naive Bayes.
* Ensemble Methods: Random Forest, XGBoost, LightGBM, CatBoost.
* Advanced Technique: Stacking (Meta-model).

3. Optimization
Usage of Optuna to search for the best hyperparameters.


