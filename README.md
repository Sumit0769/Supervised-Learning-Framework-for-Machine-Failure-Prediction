# Supervised-Learning-Framework-for-Machine-Failure-Prediction
# AI4I 2020 Predictive Maintenance Project

## Overview
This project builds a predictive maintenance model using the AI4I 2020 real-world industrial dataset.

## Objective
To predict machine failure before breakdown using sensor data.

## Dataset Features
- Air temperature
- Process temperature
- Rotational speed
- Torque
- Tool wear
- Machine Type

## Methodology
- Data preprocessing & encoding
- Standard scaling
- SMOTE for imbalance handling
- XGBoost classifier
- Stratified 5-fold Cross Validation
- GridSearchCV for hyperparameter tuning
- ROC-AUC evaluation
- SHAP explainability

## Results
- ROC-AUC: ~0.90+
- High recall for failure detection
- Torque & Tool wear identified as key drivers

## Business Impact
Enables early maintenance scheduling, reducing unplanned downtime and operational losses.
