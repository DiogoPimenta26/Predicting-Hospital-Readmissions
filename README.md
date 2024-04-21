# Predicting-Hospital-Readmissions
# Predictive Modeling for Hospital Readmissions in Diabetic Patients

## Introduction
Hospital readmissions are a critical indicator of healthcare quality, prompting the need for accurate predictive models. This project focuses on developing models to forecast hospital readmissions among diabetic patients, encompassing both binary (30-day readmission) and multiclass (timeframe of readmission) classifications.

## Data Exploration and Preprocessing
- Explored a dataset of 71,236 medical records for 53,985 American diabetic patients.
- Addressed data inconsistencies, missing values, and imbalanced target variables.
- Employed feature engineering techniques to enhance data quality and interpretability.

![output](https://github.com/DiogoPimenta26/Predicting-Hospital-Readmissions/assets/148448280/a078655d-6abb-4101-8d7f-c7f15a1f8423)

## Feature Engineering
- Transformed medication and diagnosis columns into binary features.
- Created new features such as hospital visits and medication ratios.
- Applied one-hot encoding and binary transformations for categorical features.

## Outliers and Scaling Data
- Detected outliers and applied robust scaling to mitigate their impact on model training.
- Ensured features were on comparable scales for optimized model performance.

## Feature Selection
- Utilized variance checking, correlation analysis, and recursive feature elimination for feature selection.
- Selected 51 features through a combination of methods including random forest feature importance and Lasso regression.

![Feature importance](https://github.com/DiogoPimenta26/Predicting-Hospital-Readmissions/assets/148448280/1a0cdba5-04af-401c-bb14-3a99ca16fee0)

## Binary Classification
- Tested various models including Decision Trees, Logistic Regression, and Ensemble methods.
- Employed random search for hyperparameter optimization, considering F1-score as the evaluation metric.


![Binary Scores](https://github.com/DiogoPimenta26/Predicting-Hospital-Readmissions/assets/148448280/526e0a0b-31aa-43b3-b926-fcb9f4a82504)

## Multiclass Classification
- Applied similar models for multiclass classification, emphasizing Random Forest for its superior performance.
- Utilized weighted F1-score to account for class imbalances, ensuring fair evaluation across all classes.

![Multiclass Scores](https://github.com/DiogoPimenta26/Predicting-Hospital-Readmissions/assets/148448280/c023c43a-ac97-4bd0-90f3-4cdb0bf26519)

## Conclusion
- The final Random Forest model demonstrated promising results in both binary and multiclass classifications, indicating favorable predictive performance.
- Challenges encountered included imbalanced classes and computational constraints, necessitating careful model selection and evaluation.
- Future research avenues include exploring alternative imputation methods and refining feature engineering strategies.

This repository contains code, data, and documentation for the project. For detailed implementation and findings, refer to the corresponding notebooks and reports.
