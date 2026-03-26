# Student Stress Predictor

ML classification pipeline to predict student stress levels from behavioral and academic indicators.

## Problem

Student stress is a growing concern in higher education. Early identification of at-risk students using data-driven signals can support timely intervention.

## Approach

- Collected and cleaned 5,000+ structured student records
- Performed feature engineering to identify top stress indicators
- Benchmarked 4 classification models (Logistic Regression, Decision Tree, Random Forest, SVM)
- Selected best model using F1-score and ROC-AUC to account for class imbalance
- Identified top 5 predictive features influencing stress levels

## Results

| Metric | Score |
|--------|-------|
| Best model accuracy | 84% |
| Evaluation metrics | F1-score, ROC-AUC |
| Dataset size | 5,000+ records |
| Models compared | 4 |

## Tech Stack

Python · Pandas · Scikit-learn · SQL · Matplotlib

## Setup

```bash
git clone https://github.com/5ushh/student-stress-predictor
cd student-stress-predictor
pip install pandas scikit-learn matplotlib
python train.py
```

## Note

Developed as part of ML coursework at NYU (Dec 2025).
