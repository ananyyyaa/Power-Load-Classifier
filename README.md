# Load_Type Prediction Using Machine Learning
# Project Pipeline

1. Data Cleaning
Parse `Date_Time` column
Fill missing values using column-wise median
Strip column names for consistency

2. Feature Engineering
Extract `Month` from timestamp

3. Train-Test Split
Uses last month’s data as test set
Ensures time-order is respected 

4. Model
Random Forest Classifier 
Chosen for robustness and interpretability

5. Evaluation
Accuracy
Classification Report - precision, recall, f1-score
Confusion Matrix (visualized)

#  Output Confusion Matrix

Confusion matrix showing predicted vs actual Load_Type values.

# Installation

pip install -r requirements.txt
