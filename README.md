# Heart Disease Prediction (AI-PROJECT-major)

Simple heart disease prediction project built in a Jupyter notebook with data preprocessing, model training, evaluation, and a prediction helper.

## Contents
- Dataset: [heart.csv](AI-PROJECT-major/heart.csv)  
- Notebook: [HeartDiseasePrediction.ipynb](AI-PROJECT-major/HeartDiseasePrediction.ipynb) — contains preprocessing, training, feature analysis, model export, and a prediction function [`predict_heart_disease`](AI-PROJECT-major/HeartDiseasePrediction.ipynb).

## Quick start
1. Open and run the notebook: [AI-PROJECT-major/HeartDiseasePrediction.ipynb](AI-PROJECT-major/HeartDiseasePrediction.ipynb).  
2. The notebook saves artifacts via joblib (example lines: `joblib.dump(rf, 'heart_disease_model.pkl')`, `joblib.dump(scaler, 'scaler.pkl')`).

## Prediction usage
The notebook implements a helper [`predict_heart_disease`](AI-PROJECT-major/HeartDiseasePrediction.ipynb) that:
- loads the trained model and scaler,
- accepts the clinical inputs (age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal),
- returns a human-readable result.

Open the notebook to see the exact function signature and example call.

## Requirements
- Python 3.x
- pandas, numpy, scikit-learn, matplotlib, seaborn, joblib

Install via:
```sh
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```
