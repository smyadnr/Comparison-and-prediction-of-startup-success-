# Comparison-and-prediction-of-startup-success-
Comparison and prediction of startup success criteria using various statistical and machine learning models

This project investigates the prediction of startup success using the Kaggle Startup Success Prediction dataset, which includes 923 observations and 49 features spanning financial, organizational, and geographic factors. Exploratory data analysis highlighted key patterns, that includes the importance of milestone achievement, team size, and professional networks, as well as geographic and funding-related trends.

GOAL: Identify key factors influencing success while providing insights for investment strategy and resource allocation.

DATA: startup data.csv(210.06 kB)
https://www.kaggle.com/datasets/manishkc06/startup-success-prediction/data

TOOLS:
Python, R, Tableau 

MODELS: 
Logistic Regression, Decision Tree, Random Forest, k-nearest neighbors, Naïve Bayes, Support Vector Machine, XGBoosting 


RESULTS:
- Exploratory data analysis highlighted key patterns, that includes the importance of milestone achievement, team size, and professional networks, as well as geographic and funding-related trends.
- Various machine learning and statistical models - logistic regression, decision tree, random forest, k-nearest neighbors, naive bayes, support vector machine, and XGBoost were trained on a 70-30 train-test split, with hyperparameter tuning via cross-validation.
- Model performance was evaluated using ROC-AUC, F1 score, and accuracy metrics, while class imbalance and SMOTE was tested in handful of models but not adopted for the whole analysis.
- Random forest emerged as the best-performing model, followed by decision tree and boosting, both achieving metrics better than the standard benchmarks (ROC-AUC ≥ 0.75, F1 ≥ 0.70, accuracy ≥ 0.70) in literature.
