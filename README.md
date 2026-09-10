# MSc Applied AI — Student Dropout Prediction

**University of Westminster | MSc Applied AI | 2026**
**Student:** Usama Haji Jabeen (W2176726)
**Supervisor:** Mahmoud Aldraimli

## Research Question
Can enrollment and first semester features predict 
student dropout and improve upon the benchmark 
established by Martins et al. 2023?

## Dataset
UCI Predict Students Dropout and Academic Success
Realinho et al. 2022 — 4,424 students, 37 variables

## Models
- Random Forest
- XGBoost  
- LightGBM

## Results
| Model | F1 Dropout | AUROC | Accuracy |
|-------|-----------|-------|----------|
| Random Forest | 0.8506 | 0.9482 | 0.8829 |
| XGBoost | 0.8715 | 0.9576 | 0.8981 |
| LightGBM | 0.8621 | 0.9552 | 0.8898 |

**Martins 2023 Benchmark: 0.745**
**All three models beat the benchmark significantly**

## Notebooks
1. `01_eda.ipynb` — Exploratory Data Analysis
2. `02_preprocessing.ipynb` — Data Preprocessing
3. `03_models.ipynb` — Model Training and Tuning
4. `04_evaluation.ipynb` — Model Evaluation
5. `05_shap.ipynb` — SHAP Analysis and Real World Demo

## Requirements
pip install -r requirements.txt
