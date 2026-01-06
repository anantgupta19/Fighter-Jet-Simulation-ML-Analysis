# ✈️ Fighter Jet Simulation – Machine Learning Analysis

This repository demonstrates an end-to-end **engineering + machine learning workflow**, where aerodynamic simulation data from a fighter jet model is used to build, evaluate, and compare ML models.

Unlike typical ML projects based on public datasets, this work is built on a **custom dataset generated from an actual SolidWorks simulation**, making it closer to real-world engineering and industry ML pipelines.

---

## 🔍 Project Overview

The project bridges two domains:

- **Engineering**: Fighter jet design and simulation (SolidWorks)
- **Data Science & ML**: Analysis, modeling, and performance evaluation

The goal is to understand how simulated design parameters influence performance metrics and how effectively machine learning models can learn these relationships.

---

## 🧠 What Was Done

### 1. Data Preparation
- Structured raw simulation outputs into a usable tabular format
- Handled noise and inconsistencies typical of simulation-generated data

### 2. Exploratory Data Analysis (EDA)
- Studied relationships between design parameters and performance metrics
- Identified trends, correlations, and sensitivity of variables

### 3. Feature Engineering
- Selected and refined features based on aerodynamic intuition
- Prepared data for stable and meaningful model training

### 4. Model Training
- Trained multiple regression-based ML models
- Focused on interpretability and generalization

### 5. Model Evaluation
- Compared models using standard error metrics:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - RMSE (Root Mean Squared Error)
- Analyzed trade-offs between accuracy and robustness

---

## 🧰 Tech Stack

- **Python**
- **NumPy, Pandas** – data handling  
- **Matplotlib / Seaborn** – visualization  
- **Scikit-learn** – modeling and evaluation  

---

## 🔑 Key Learning

> **This was my first time working on a fully custom dataset generated from an engineering simulation rather than a pre-existing online dataset.**

That shift required a different mindset—handling assumptions carefully, validating results more rigorously, and treating the data as a product of physics rather than just numbers.

---

## 📊 Workflow Snapshot

Engineering Design → Simulation → Dataset Creation → EDA → Feature Engineering → ML Modeling → Error Analysis → Insights

---

## 🚀 Why This Matters

This project reflects how **AI can meaningfully integrate with core engineering domains** when the pipeline is designed correctly. It’s a small but solid step toward industry-grade engineering intelligence systems.

More iterations and deeper integrations are underway.

---

## 📈 Future Direction (Intentionally Vague 😉)

This work is part of a broader collaboration exploring tighter coupling between simulation-driven engineering and machine learning. What’s coming next builds on this foundation—bigger scope, deeper modeling, and more realism.

Stay tuned.


