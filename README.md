# Heart Disease Prediction (AI-PROJECT-major)

Simple heart disease prediction project implemented as a Jupyter notebook with data preprocessing, model training, evaluation, and a prediction helper.

## Table of contents
- [Project overview](#project-overview)  
- [Features](#features)  
- [Contents](#contents)  
- [Requirements](#requirements)  
- [Quick start](#quick-start)  
- [Usage examples](#usage-examples)  
  - [Run the notebook](#run-the-notebook)  
  - [Programmatic prediction (Python)](#programmatic-prediction-python)  
  - [Command-line example](#command-line-example)  
- [Model artifacts](#model-artifacts)  
- [Dataset & preprocessing](#dataset--preprocessing)  
- [Evaluation & results](#evaluation--results)  
- [Project structure](#project-structure)  
- [Testing](#testing)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

## Project overview
This repository demonstrates a data-science workflow for predicting presence of heart disease from clinical features (age, sex, chest pain type, blood pressure, cholesterol, etc.). The main work is contained in a Jupyter notebook that covers EDA, preprocessing, model selection, training, evaluation, and exporting trained artifacts.

## Features
- End-to-end notebook with EDA and model training
- Model export (joblib) for reuse
- Scaler/exported preprocessing for consistent predictions
- Prediction helper function to make single or batch predictions
- Basic evaluation metrics and plots

## Contents
- Dataset: AI-PROJECT-major/heart.csv  
- Notebook: AI-PROJECT-major/HeartDiseasePrediction.ipynb — includes preprocessing, training, feature analysis, model export, and prediction helper.

## Requirements
- Python 3.8+ recommended
- packages: pandas, numpy, scikit-learn, matplotlib, seaborn, joblib, jupyter

Install them with:
```sh
pip install pandas numpy scikit-learn matplotlib seaborn joblib jupyter
```

