## Depression Risk Detection - ML for Healthcare (Text)

Proyecto: Pipeline de Machine Learning para detección de riesgo de depresión/anxiety a partir de textos.

Contenido:
- notebooks/01_depression_ml_colab.ipynb : Notebook listo para Colab.
- data/raw : datasets originales (no incluidos).
- models : modelos entrenados.
- results : figuras y métricas.

Objetivo: demostrar pipeline reproducible, modelos baseline (Logistic Regression, XGBoost) y explicabilidad (SHAP).

Instrucciones rápidas:
1. Clona repo.
2. Sube tu kaggle.json a ~/.kaggle/ en Colab.
3. Ejecuta el notebook `01_depression_ml_colab.ipynb`.


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
