# Diabetes Prediction Project

## About the Project
This project predicts whether a person has diabetes or not using machine learning.

---

## Files in This Project
- diabetes.csv - Dataset
- notebook.ipynb - Main Jupyter Notebook code
- graphs - Folder containing saved graphs
- README.md - Project documentation

---

## Dataset Information
The dataset contains medical features such as:
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Age
- Outcome (0 = No Diabetes, 1 = Diabetes)

---

## Data Cleaning
- Replaced zero values with missing values (NaN)
- Filled missing values using mean of each column

---

## Data Visualization
The following graphs are created:
- Outcome distribution
- Correlation heatmap
- Confusion matrix
- ROC curve

All graphs are saved in the graphs folder.

---

## Machine Learning Model
- Model used: Random Forest Classifier
- Train-test split: 80% training, 20% testing
- Evaluation methods:
  - Accuracy
  - Confusion Matrix
  - ROC Curve

---

## Goal of the Project
To predict diabetes based on medical data using machine learning.

---

## How to Run the Project
1. Open Jupyter Notebook
2. Open notebook.ipynb
3. Run all cells step by step

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn