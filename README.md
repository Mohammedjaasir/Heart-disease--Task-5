## 🌳 Heart Disease Prediction - Decision Trees & Random Forests (Task 5)

> This project implements **Decision Tree** and **Random Forest** classifiers to predict heart disease presence using patient data. It explores tree visualization, overfitting control, feature importance, and model evaluation with cross-validation.

---

## 📁 Dataset
- Source: [Heart Disease Dataset (Kaggle)](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Target: `target` (1 = heart disease, 0 = no heart disease)
- Features: Age, sex, chest pain type, blood pressure, cholesterol, etc.

---

## 🎯 Objectives
- Train and visualize a Decision Tree Classifier
- Prevent overfitting using `max_depth`
- Train a Random Forest and compare performance
- Interpret feature importances
- Evaluate both models using accuracy and cross-validation

---

## 🧰 Tools & Libraries
| Tool             | Purpose                           |
|------------------|-----------------------------------|
| Pandas           | Data handling                     |
| Matplotlib/Seaborn | Data visualization              |
| Scikit-learn     | Machine learning models & metrics |

---

## 🔄 Workflow Summary

1. **Data Exploration**
    - Checked data types, nulls, correlations
2. **Preprocessing**
    - Target-feature split, train-test split
3. **Decision Tree**
    - Trained base model, visualized tree
    - Limited depth to reduce overfitting
4. **Random Forest**
    - Compared performance with ensemble method
5. **Feature Importance**
    - Bar chart from Random Forest
6. **Cross-Validation**
    - 5-fold CV to validate performance stability

---

## 📊 Key Visuals

- ✅ Full Decision Tree Diagram
- 📉 Pruned Tree Accuracy Comparison
- 🌲 Random Forest Feature Importance Plot
- 📋 Confusion Matrix & Classification Report

---

## 💡 Key Insights

- **Decision Trees** are highly interpretable but can overfit.
- **Random Forests** offer better generalization with slightly better accuracy.
- Features like `cp` (chest pain), `thal`, and `ca` were most important.
- Pruning decision trees improved test performance.

---

## 📂 Project Structure

📁 decision-tree-random-forest
│
├── heart.csv # Dataset
├── task5_decision_tree_random_forest.py # Python script
├── README.md # This file

---

## 🚀 How to Run
1. Clone this repo
2. Install dependencies:  
   `pip install pandas scikit-learn matplotlib seaborn`
3. Run:  
   `python task5_decision_tree_random_forest.py`

---

## ✨ Final Thoughts
This task helps build intuition behind tree-based models — how they split, when they overfit, and why ensembles like random forests perform better in real-world tasks.
