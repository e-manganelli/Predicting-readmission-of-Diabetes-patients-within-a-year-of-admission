# Predicting Diabetes Patient Readmission Within One Year Using Machine Learning Models

This project uses a dataset of diabetes patient hospital records to predict the likelihood of readmission within a year of the initial admission. Unlike prior research focused on early readmission (within 30 days), this study extends the prediction window to one year, aiming to identify factors contributing to long-term readmission risk, which may indicate mismanagement of a patient's diabetes.

## Data Preprocessing

Dataset: Contains 101,766 patient encounters with 50 variables. \
Preprocessing: Included handling missing data, identifying unique patient encounters, medication variable analysis, age group processing, ICD-9 code categorization for diagnoses, feature selection using entropy analysis, and encoding categorical variables.\
Final Dataset: 23 features used for modeling.
## Methodologies

Six machine learning models were trained and evaluated:

Logistic Regression and Lasso Regression: Used for feature selection and baseline performance.\
Neural Network: A simple feed-forward neural network to capture non-linear patterns.\
Decision Tree: Provides an interpretable model with direct insights into feature importance.\
Random Forest: An ensemble method to improve generalizability and predictive power.\
XGBoost: A gradient boosting model to enhance performance using sequential tree building.\
## Results

Performance: Models achieved an accuracy of around 60%, with XGBoost achieving the highest accuracy at 62.3%.\
Feature Importance: Age, number of previous hospital visits, and the number of diagnoses were key predictors of readmission.\
Sensitivity: The models showed high sensitivity, important in healthcare to avoid underestimating patient risk.\
## Conclusion

The study provides insights into factors influencing long-term readmission in diabetes patients, suggesting that older patients with frequent hospital admissions are at higher risk. Despite modest model performance, the findings can inform healthcare providers to implement targeted interventions.
