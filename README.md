# Patient Readmission Prediction (Healthcare)
📌 Project Overview

Hospital readmissions within 30 days are a critical quality and cost metric in healthcare. This project uses machine learning to predict whether a patient will be readmitted after discharge.

The goal is to:

Support clinicians and hospital administrators with data-driven insights

Reduce unnecessary readmissions (improving patient outcomes)

Lower healthcare costs and optimize resource allocation

Two interpretable models were implemented and compared:

Logistic Regression

Decision Tree Classifier

🛠️ Tools & Technologies

Python 🐍

Libraries:

pandas, numpy → Data cleaning & manipulation

scikit-learn → Logistic Regression, Decision Trees, evaluation metrics

matplotlib, seaborn → Data visualization

jupyter → Interactive development

📂 Dataset

Features:

Demographics (age, gender, race)

Target: Readmission → Whether a patient was readmitted within 30 days (Yes/No)

⚙️ Methodology

Data Preprocessing

Removed irrelevant features (e.g., encounter IDs)

Encoded categorical variables (gender, admission type, etc.)

Handled missing values


Exploratory Data Analysis (EDA)

Patient age distribution

Readmission rates by diagnosis, gender, and age group

Correlation heatmaps for key features

Modeling

Train-test split (80% training / 20% testing)

Logistic Regression classifier

Decision Tree classifier (with max depth tuning)

Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix

ROC-AUC score
