# Acute Kidney Injury Risk Analysis After Cardiac Surgery

Exploratory and predictive analysis of factors contributing to acute kidney injury (AKI)
development in patients following major cardiac surgery.

## Overview

Post-operative AKI is a life-threatening complication observed after complex cardiac
procedures. This project investigates clinical, hematological, and surgical parameters
that influence kidney function in the post-operative period.

## Contents

♡ Full EDA with visualization of patient and surgery-related features  
♡ Literature review with references to medical studies  
♡ CatBoost regression model predicting glomerular filtration rate (GFR)  
♡ Feature importance analysis and model evaluation  

## Top Predictive Features

| Feature | Importance |
|---|---|
| Chronic kidney disease (CKD) | 51.4 |
| Blood creatinine | 11.2 |
| Age | 7.2 |
| BMI | 4.0 |
| LV myocardial mass | 3.1 |
| End-diastolic volume | 1.9 |

> CKD ranks highest as it is directly derived from GFR. Creatinine and age follow
> because they are the primary inputs in GFR calculation formulas (CKD-EPI / MDRD).

## Stack
![NumPy](https://img.shields.io/badge/NumPy-D6759E?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-D6759E?style=for-the-badge&logo=pandas&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-D6759E?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikitlearn-D6759E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Python](https://img.shields.io/badge/Python-D6759E?style=for-the-badge&logo=Python&logoColor=white)

## Data

De-identified clinical dataset including pre- and post-operative blood tests,
patient health indicators, and surgery parameters.
