
# CodeAlpha Machine Learning Internship

## Task 4: Disease Prediction from Medical Data

**Objective:** Predict the possibility of disease (breast cancer — malignant vs benign) based on patient diagnostic data.

**Dataset:** Breast Cancer Wisconsin (Diagnostic) Dataset — UCI ML Repository (bundled with scikit-learn). 569 patients, 30 numeric features extracted from cell nuclei measurements.

**Approach:** Applied classification techniques to structured medical data using multiple algorithms and compared performance.

**Algorithms used:**
- Logistic Regression
- Random Forest
- SVM (RBF kernel)

**Evaluation metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix

## Results

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---|---|---|---|---|
| Logistic Regression | 98.2% | 98.6% | 98.6% | 98.6% | 0.995 |
| SVM (RBF) | 98.2% | 98.6% | 98.6% | 98.6% | 0.995 |
| Random Forest | 95.6% | 95.9% | 97.2% | 96.6% | 0.993 |

See `results.png` for ROC curves and feature importance chart, and `model_comparison.csv` for full metrics.

## How to run
