# Telco-Churn-Prediction

## Objective
Business Problem: Predict which customers are likely to cancel services to enable targeted retention campaigns.  
ML Task: Binary classification (Churn: Yes/No)  
Success Metrics:
- F1-score > 0.60 (handling class imbalance)
- Accuracy > 80%
- ROC AUC > 0.75

## Methodology
### Data Pipeline
graph TD
    A[Raw Data] --> B[Data Cleaning]
    B --> C[Feature Engineering]
    C --> D[Train-Test Split]
    D --> E[Model Training]
    E --> F[Evaluation]
