"""
Task 4: Disease Prediction from Medical Data
CodeAlpha Machine Learning Internship

Objective: Predict the possibility of disease (breast cancer - malignant vs benign)
based on patient diagnostic data.

Dataset: Breast Cancer Wisconsin (Diagnostic) Dataset - UCI ML Repository
(bundled with scikit-learn, 569 patients, 30 numeric features from cell nuclei measurements)

Algorithms: Logistic Regression, Random Forest, SVM
Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix
"""

import numpy as np
import pandas as pd
from sklearn.datasets import load_breast_cancer
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomFores
