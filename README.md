# Syntactic Processing Assignment

# 🥘 Recipe NER Model using CRF

This project focuses on identifying key entities in structured recipe data using a Named Entity Recognition (NER) model based on Conditional Random Fields (CRF). The goal is to extract entities like **ingredients**, **quantities**, and **units** from unstructured recipe ingredient text.

## 🚀 Features

- Preprocessing of structured JSON recipe data
- Exploratory Data Analysis (EDA) on tokens, POS labels
- Feature engineering using spaCy + regex
- Conditional Random Fields (CRF) for NER
- Class weighting for imbalanced labels
- Model evaluation (confusion matrix, accuracy, misclassifications)
- Error analysis and insights
- Final report generation (PDF)

## 📊 Labels Extracted

- `ingredient`
- `quantity`
- `unit`

## 🧪 Libraries Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `sklearn-crfsuite`, `scikit-learn`
- `spaCy`
- `joblib`, `json`

## 📈 Results
- CRF trained on structured ingredient data

- Validation accuracy achieved with class-weighted loss

- Misclassifications analyzed and visualized

- Final CRF model saved (crf_model.pkl)
