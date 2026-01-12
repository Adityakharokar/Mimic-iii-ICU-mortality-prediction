# Mimic-iii-ICU-mortality-prediction
Machine learning-based prediction of ICU patient in-hospital mortality using the MIMIC-III clinical dataset.

-- Problem Statement

Predict in-hospital mortality of ICU patients using clinical and
administrative data to understand factors associated with higher
mortality risk.

-- Dataset
- Source: MIMIC-III Clinical Database
- Type: Healthcare / ICU patient data
- Description: Contains patient stays, ICU admissions, lab events,
  medications, and hospital outcomes.

-- Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn

-- Approach
- Performed exploratory data analysis to understand patient stay patterns
  and mortality distribution.
- Engineered features such as ICU length of stay, hospital duration,
  lab event counts, and medication counts.
- Built a baseline Bernoulli Naive Bayes model to establish initial
  performance.
- Applied hyperparameter tuning to improve classification performance.
- Trained a Random Forest Classifier to capture non-linear relationships
  and feature interactions.

-- Results
- Baseline Bernoulli Naive Bayes achieved **~79% accuracy** with mortality
  class F1 ≈ 0.56.
- Tuned model improved to **~87% accuracy** with mortality class F1 ≈ 0.76.
- Random Forest Classifier achieved **~92% accuracy** with mortality class
  F1 ≈ 0.80.

-- Key Learnings
- Handling class imbalance and evaluating models beyond accuracy.
- Importance of recall and F1-score in healthcare prediction tasks.
- Interpreting clinical features in a meaningful, domain-aware manner.
