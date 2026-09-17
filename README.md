# intern-performance-prediction-
Machine learning project that predicts intern success probability using attendance, task completion, feedback, and mentor interaction data.
# Intern Performance Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning to predict intern performance based on engagement and task completion.

The model analyzes attendance, task completion, feedback, and mentor interactions to estimate an intern's probability of success and identify interns who may need additional support.

## Objective

* Predict intern performance using Machine Learning
* Estimate success probability
* Identify different risk levels
* Provide personalized guidance for mentors
* Practice machine learning with Python and Scikit-learn

## Dataset

The project contains data for 50 interns.

The main features include:

* Attendance (%)
* Tasks Submitted
* Tasks Assigned
* Task Completion (%)
* Feedback Level
* Feedback Score
* Mentor Interactions
* Outcome

## Machine Learning Model

The project uses **Logistic Regression** with Scikit-learn.

The workflow includes:

1. Data loading
2. Data cleaning
3. Missing-value checking
4. Duplicate checking
5. Feature selection
6. Train-test split
7. Feature scaling
8. Model training
9. Success probability prediction
10. Model evaluation
11. Risk classification
12. Mentor recommendations

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

## Mentor Guidance

The project generates recommendations based on predicted risk:

* **High Risk:** Schedule one-to-one mentoring and review unfinished tasks.
* **Medium Risk:** Increase feedback frequency and monitor task completion.
* **Low Risk:** Maintain support and consider advanced assignments.

## Key Learning

This project demonstrates how machine learning can transform internship engagement data into useful insights for mentors and help identify interns who may benefit from additional guidance.

## Project Files

```text
Intern_Performance_Prediction.ipynb
Intern_Performance_Prediction_Dataset.csv
Intern_Performance_Prediction_ML.py
README.md
```

## Note

The dataset is synthetic and is intended for learning and demonstration purposes.

## Author

**Sheeba Kousar**

Aspiring Data Analyst | Python | Power BI | Excel | Machine Learning
