# Instructor Effectiveness Prediction

This project analyzes instructor performance data and builds a machine learning model to classify instructors into **Low, Medium, and High effectiveness tiers** using engagement, learning outcome, and feedback metrics.

## Overview

The analysis follows a structured data science workflow:

- Exploratory Data Analysis (EDA)
- Feature aggregation from batch level to instructor level
- Instructor effectiveness tier creation
- Machine learning model training and evaluation
- Feature importance analysis and interpretation

A **Random Forest classifier** is used to predict instructor effectiveness tiers. Special attention was given to identifying and removing **target leakage** to ensure realistic model performance.

## Results

The final model achieved approximately **90% cross-validation accuracy**, with learning outcomes and student engagement metrics emerging as the most influential predictors.

## Repository Contents

- `instructor_effectiveness_modeling.ipynb` – Complete analysis, modeling, explanations, and conclusions
- `dataset.csv` – Instructor performance dataset used for the analysis

All methodology, insights, assumptions, and limitations are documented within the notebook.
