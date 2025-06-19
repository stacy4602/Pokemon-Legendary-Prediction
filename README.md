# 🧠 Pokémon Legendary Prediction

This is a machine learning project developed in a **Jupyter Notebook** to predict whether a Pokémon is **Legendary** or not based on its attributes.

---

## 📌 Project Overview

The goal is to explore Pokémon data and build a classification model that can identify legendary Pokémon using various statistical and categorical features.

---

## 📁 Dataset

- The dataset includes details such as:
  - Name, Type 1, Type 2
  - Total, HP, Attack, Defense, Sp. Atk, Sp. Def, Speed
  - Generation, Legendary (target variable)
- Source: Kaggle
---

## 🔍 Exploratory Data Analysis (EDA)

- Analyzed distribution of base stats across legendary and non-legendary Pokémon
- Visualized type frequencies and relationships
- Handled null values and encoded categorical features

---

## 🧠 Model Building

- **Preprocessing**:
  - Label encoding for types and generation
  - Feature scaling using `StandardScaler`
- **Models Used**:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost Classifier
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix

---

## 🛠 Technologies Used

- Python (Jupyter Notebook)
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

