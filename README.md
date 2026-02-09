# Predictive Maintenance using XGBoost

## Overview

This project builds a machine learning model to predict machine failure using operational and environmental sensor data.

Predictive maintenance is widely used in manufacturing and heavy equipment industries, such as automotive production and industrial machinery, to reduce downtime and maintenance costs.

This project demonstrates an end-to-end data science pipeline, including:

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Feature engineering
* Machine learning modeling using XGBoost
* Model evaluation
* Feature importance analysis
* Business insight generation

---

## Dataset

Machine Predictive Maintenance Classification Dataset (AI4I Predictive Maintenance Dataset 2020)

Features include:

* Air temperature
* Process temperature
* Rotational speed
* Torque
* Tool wear
* Machine type

Target:

* Machine failure (0 = No Failure, 1 = Failure)

---

## Model

Model used:

* XGBoost Classifier

---

## Model Performance

* Accuracy: 98.35%
* Precision: 76.9%
* Recall: 65.6%
* F1 Score: 70.8%

The model successfully identifies potential machine failures while maintaining a relatively low false positive rate.

---

## Feature Importance

Key factors influencing machine failure:

* Torque
* Air temperature
* Tool wear
* Rotational speed

This aligns with real-world mechanical failure patterns.

---

## Business Impact

This model can help organizations:

* Reduce unexpected machine downtime
* Optimize maintenance scheduling
* Reduce maintenance costs
* Improve operational efficiency

---

## Tech Stack

* Python
* Pandas
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Google Colab

