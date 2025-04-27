# Predicting 30-Day Hospital Readmission: A Machine Learning Solution for Healthcare

This project is part of the **Softec Hackathon** organized by **FAST-NUCES Lahore**, where students and professionals from different universities participated. Our team ranked **13th** with an accuracy of **74%** in predicting 30-day hospital readmissions using machine learning.

## Project Overview

In this project, we developed a machine learning model to predict whether a patient will be readmitted to the hospital within 30 days of discharge. The dataset consists of various features, including diagnosis codes, procedure codes, patient demographics, and hospital stay details.

## Approach

- **Data Preprocessing**: We handled missing values, encoded categorical variables, and performed necessary transformations to ensure the dataset was suitable for machine learning.
- **Modeling**: We used **XGBoost** (Extreme Gradient Boosting) to build the model due to its high efficiency and performance on structured datasets.
- **Hyperparameter Tuning**: We optimized the model's hyperparameters using **RandomizedSearchCV** to find the best configuration for our classifier.
- **Evaluation**: The model was evaluated using metrics such as **accuracy**, **AUC-ROC**, and **classification report**.

## Key Metrics

- **Training Accuracy**: 
- **Accuracy**: 74%
- **AUC Score**: 0.97
- **Precision (0)**: 0.96
- **Precision (1)**: 0.92
- **Recall (0)**: 0.91
- **Recall (1)**: 0.96

## Confusion Matrix
![image](https://github.com/user-attachments/assets/177eeb99-aead-41f9-98fc-4c03d5301da0)

## ROC ( AUC )
![image](https://github.com/user-attachments/assets/7d143ee4-c11c-4bea-9905-55d8e3191fe2)

## Feature Extraction
![image](https://github.com/user-attachments/assets/3c786550-15cb-4392-8a0a-e3c90882ce94)

## Data

- The dataset used in this project is a part of a **hospital readmission prediction** challenge.
- It contains multiple columns related to patient demographics, diagnoses, procedures, and stay details.

## Data Distribution 

The data was heavily biased towards one class. We have to use SMOTE for upsampling the data

![image](https://github.com/user-attachments/assets/58427788-c542-467c-a93a-8065924f4cc3)

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `xgboost`, `scikit-learn`, `scipy`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NotAbdullah87/-Predicting-30-Day-Readmissions-using-XGBoost.git
