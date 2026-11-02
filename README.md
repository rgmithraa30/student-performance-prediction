# Student Performance Prediction System

A beginner-level Machine Learning internship project that analyzes student data and predicts final grades (G3) using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

## Dataset
UCI Student Performance dataset (math course): 395 students, 33 columns. No missing values or duplicates were found.

## Workflow
Data → Cleaning → EDA → Feature Selection → Training → Testing → Evaluation → Prediction

## Results
| Model | R² | MAE | RMSE |
|---|---|---|---|
| Linear Regression (without G1, G2) | 0.141 | 3.395 | 4.196 |
| Random Forest (without G1, G2) | 0.245 | 3.148 | 3.935 |
| Random Forest (with G1, G2) | 0.815 | 1.165 | 1.949 |

## Prediction System
`predict_grade()` takes a student's details (study time, failures, absences, age) and returns a predicted final grade out of 20, labeled Pass or At risk.

## Files
- `student_performance_prediction.ipynb`: full notebook
- `student-mat.csv`: dataset

## How to Run
Open the notebook in Google Colab and run all cells.
