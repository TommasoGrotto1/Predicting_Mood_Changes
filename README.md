# Predicting Mood Changes

This repository contains the complete workflow for a project investigating whether short-term mood changes can be predicted using smartphone-collected behavioral data and repeated self-reported mood assessments. The project was part of the **Studies on Human Behaviour course** and combines data cleaning, feature engineering, and machine learning modelling to identify behavioral markers of mood fluctuations.

---

## Repository Structure

```
Predicting_Mood_Changes/
│
├── SHB - Predicting mood changes.pdf # Final project report
├── SHB_cleaning.ipynb # Notebook for data cleaning & preprocessing
└── SHB_models.ipynb # Notebook with machine learning models
```

---

## Project Overview

The aim of this project is to predict within-day and next-day mood changes among university students using data collected through a custom smartphone app.  
The dataset includes:

- Repeated self-reported mood questionnaires  
- Smartphone sensor data (e.g., activity, screen usage, movement)  
- Behavioral variables derived from passive data collection  

The project explores the feasibility of predicting mood dynamics using statistical learning methods.

---

## Data Cleaning (`SHB_cleaning.ipynb`)

This notebook performs essential preprocessing steps:

- Handling missing data  
- Removing invalid or noisy observations  
- Aggregating and transforming sensor logs  
- Feature engineering and variable scaling  
- Creating mood-change labels for analysis  

The output is a structured dataset ready for model training.

---

## Machine Learning Models (`SHB_models.ipynb`)

This notebook includes:

- Train/test splits  
- Baseline logistic regression  
- Random Forest and Gradient Boosting models  
- Evaluation metrics (accuracy, F1, ROC-AUC)  
- Feature importance and model interpretation  

The results highlight which behavioral signals are most informative for predicting mood variability.

---

## Project Report

The PDF file **“SHB – Predicting mood changes.pdf”** includes:

- Theoretical background  
- Data description  
- Methodology and models used  
- Results and interpretation  
- Discussion and limitations  

It provides a complete narrative of the project.

---

## Requirements

The analysis uses standard Python scientific libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

To recreate the environment, install dependencies with:

```bash
pip install -r requirements.txt
