# Lung Cancer Risk Prediction

## Project Overview
This project leverages machine learning techniques to predict lung cancer risk at an early stage using a combination of clinical, demographic, and environmental data. Early prediction can significantly improve patient survival rates by enabling timely interventions. The project explores various machine learning models and ensemble methods, aiming to create a robust, accurate, and interpretable lung cancer risk prediction tool suitable for clinical use.

---

## Features
- Implementation of multiple machine learning algorithms:
  - Logistic Regression
  - Random Forest
  - Extra Trees
  - XGBoost
  - Gradient Boosting
  - LightGBM
  - Bagging Classifier
  - Linear Discriminant Analysis (LDA)
- Use of hybrid ensemble models:
  - Soft Voting Hybrid Model (XGBoost + Random Forest) for higher predictive accuracy.
  - Tuned XGBoost model optimized via hyperparameter search.
- Comprehensive data preprocessing including:
  - Missing data imputation
  - Label encoding for categorical variables
  - Class imbalance handling using SMOTE (Synthetic Minority Over-sampling Technique)
  - Feature engineering and correlation analysis to reduce redundancy
  - Data standardization using scaling techniques
- Rigorous model evaluation through:
  - Stratified train-test split (80%-20%)
  - 5-fold cross-validation on training data
  - Model performance metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Visualization of results including confusion matrices and ROC curves for clear performance insights.

---

## Dataset

### Sources
- Kaggle Datasets:
  - [Lung Cancer Prediction Dataset by Mahmoud Ragab Saber](https://www.kaggle.com/code/mahmoudragabsaber/lung-cancer-prediction/input)
  - [Lung Cancer Dataset by Mysarahmadbhat](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer)

### Overview
- Total records: Over 23,000 patient records in the main dataset; additional smaller dataset with 309 records.
- Data types: Numerical and categorical features.
- Class distribution: Potentially imbalanced, with fewer high-risk lung cancer cases compared to low-risk/non-cancer.

### Key Features
- Patient_ID: Unique patient identifier
- Age: Age in years
- Gender: Male/Female
- Smoking History: Current Smoker, Former Smoker, Never Smoked
- Tumor Size (mm)
- Tumor Location: Anatomical site (e.g., Lower Lobe)
- Cancer Stage: e.g., Stage I, III, IV
- Treatment Type: Surgery, Chemotherapy, Radiation therapy, etc.
- Survival Months: Duration post-diagnosis or treatment
- Ethnicity
- Insurance Type
- Family History of cancer
- Performance Status: Clinical health score
- Additional comorbidities (Diabetes, Hypertension, Heart Disease)
- Relevant laboratory values (Glucose, Potassium, Sodium levels)
- Smoking Pack Years

---

## Getting Started

### Prerequisites
- Python 3.8 or newer
- Jupyter Notebook (optional, for interactive exploration)
- Install dependencies using:
