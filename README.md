# 🧠 Decision Tree Classifier for Patient Classification and Drug Prescription

This repository contains a machine learning project that demonstrates the implementation of a **Decision Tree Classifier** using **scikit-learn**. The classifier is trained to predict the class of a patient or recommend a drug based on various features such as demographic or clinical data. This model can serve as a foundational tool in decision support systems for healthcare applications.

---

## 🎯 Objective

To develop an interpretable and modular decision tree model capable of:
- Classifying patients based on medical or demographic attributes
- Recommending appropriate drug prescriptions for new patients
- Analyzing how changes in hyperparameters impact model behavior and performance

---

## 🛠️ Technologies Used

- Python
- scikit-learn
- pandas, NumPy
- Optional: `matplotlib`, `graphviz`, or `plot_tree` for tree visualization

---

## 📂 Dataset

- A structured dataset with patient features such as age, blood pressure, cholesterol levels, etc., and a target label representing either patient classification or the prescribed drug.
- Format: CSV or DataFrame compatible with `scikit-learn` models.

---

## 🔁 Workflow Overview

1. **Data Preparation**
   - Load and preprocess dataset
   - Encode categorical features if necessary
   - Split data into training and test sets

2. **Model Implementation**
   - Train a `DecisionTreeClassifier` from `scikit-learn`
   - Tune hyperparameters such as `max_depth`, `min_samples_split`, and `criterion`

3. **Model Evaluation**
   - Evaluate using metrics such as accuracy, precision, recall, and F1-score
   - Analyze results with a confusion matrix

4. **Visualization**
   - Visualize decision boundaries and tree structure to understand feature splits and decision paths
