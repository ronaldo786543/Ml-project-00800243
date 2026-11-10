Machine Learning Project
Student Roll Number
[00800243]

Overview
This project applies machine learning techniques to the Adult Census Income dataset.

Two prediction tasks were completed:

Classification Task
Predict whether an individual earns more than $50,000 annually.

Regression Task
Predict the number of hours worked per week.

The project follows the CRISP-DM workflow and includes data preprocessing, exploratory data analysis, model training, evaluation, interpretation, and ethical reflection.

Classification Models
Logistic Regression (L2)
Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier
Best Classification Model
XGBoost Classifier

Metric	Score
Accuracy	86.89%
Precision	77.59%
Recall	64.03%
F1 Score	70.16%
Regression Models
Linear Regression
Ridge Regression
Decision Tree Regressor
Random Forest Regressor
XGBoost Regressor
Best Regression Model
XGBoost Regressor

Metric	Score
MAE	7.31
RMSE	10.62
R²	0.266
Project Structure
data/
notebooks/
models/
results/
mlruns/
Saved Models
best_classifier.pkl
best_regressor.pkl
Results
Output tables and figures are available in:

results/
├── figures/
└── tables/
Requirements
Install dependencies using:

pip install -r requirements.txt