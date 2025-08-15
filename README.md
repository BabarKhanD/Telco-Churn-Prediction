# telco-churn-prediction-devhub  
  
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

## Acknowledgments
This project was completed with technical guidance and infrastructure support from **DeveloperHub Corporation**, whose expertise in machine learning pipelines was instrumental in achieving the model's performance metrics.

## Key Results
| Metric        | Score  | Contributor        |
|---------------|--------|--------------------|
| Accuracy      | 0.812  | DeveloperHub Team  |
| F1-score      | 0.611  | DeveloperHub Team  | 

## License
Copyright © 2023 DeveloperHub Corporation. Shared under MIT License.
