# Depression Risk Prediction with Machine Learning (Healthcare Project)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MarinaVBsc/depression-ml-project/blob/main/depression_ml_notebook.ipynb)

## Descripción
Este proyecto implementa un **modelo de Machine Learning para la detección de riesgo de depresión y ansiedad** utilizando datos de texto clínico o comportamiento/psicometría.  
El notebook combina preprocesamiento de texto, vectorización TF-IDF, modelos baseline (Logistic Regression), XGBoost, y técnicas de interpretabilidad (SHAP).

El objetivo es demostrar habilidades en **ML aplicado a healthcare**, ideal para proyectos de salud digital y análisis de datos clínicos.

---

## Dataset
- El notebook asume un CSV con columnas:
  - `text`: texto clínico o notas de comportamiento
  - `label`: etiqueta binaria (0 = sin riesgo, 1 = riesgo de depresión/ansiedad)
- Puedes usar datasets públicos de salud mental, por ejemplo:
  - [i2b2 NLP datasets](https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/)  
  - [Open Depression Dataset](https://www.kaggle.com/datasets)
- **No se incluyen datos sensibles en este repositorio.**

---

## Requisitos
Instala las librerías necesarias:

```bash
pip install pandas numpy scikit-learn xgboost shap nltk spacy joblib matplotlib seaborn
python -m spacy download en_core_web_sm


## Project structure

``` bash

depression-ml-project/
├── data/
│   ├── raw/                # dataset original (Kaggle .csv)
│   └── processed/          # datos limpios listos para modelado
├── notebooks/
│   └── 01_depression_ml_colab.ipynb
├── models/
│   └── model_xgb.pkl
├── results/
│   ├── figures/
│   └── metrics.json
├── README.md
└── requirements.txt
```
