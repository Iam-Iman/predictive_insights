# Predictive Insights - Youth Employment Project

## Project Overview

This documentation outlines the Predictive Insights project, which involved the development of two machine learning models using Random Forest Classifier and XGBoost Classifier. The objective was to predict youth employment based on data from labor market surveys in South Africa. This documentation follows the Team Data Science Process (TDSP) Lifecycle stages and provides insights into the project's scope, plan, personnel, metrics, data acquisition, understanding, modeling, and deployment.

## 1. Business Understanding

### Problem Definition

The primary goal of this project was to create predictive models for youth employment outcomes in South Africa using machine learning techniques. Two models, Random Forest Classifier and XGBoost Classifier, were developed to predict employment status based on demographic and labor market features.

### Scope

- Development of two binary classification models (Random Forest and XGBoost).
  
### Plan

The project closely followed the TDSP lifecycle stages. It involved a data scientist. Model performance was evaluated using ROC AUC score.

## 2. Data Acquisition and Understanding

### Raw Data

The dataset used for this project contained information from four rounds of a survey of youth in the South African labor market, conducted at 6-month intervals. The dataset included numerical, categorical, and free-form text responses, as well as demographic information such as age and education level. Two datasets, Train.csv and Test.csv were used.

### Data Exploration

Data exploration involved understanding the dataset's characteristics, distributions, and relationships between features. Key insights were derived using descriptive statistics and visualizations.

## 3. Modeling

### Feature Engineering

- Data preprocessing, including handling missing values and encoding categorical features.
- New features creation.
- Standardization of numerical features.

### Modeling Training

Two machine learning models were trained: Random Forest Classifier and XGBoost Classifier. Hyperparameter tuning was conducted for both models to optimize their performance.

### Model Evaluation

Model performance was assessed using ROC AUC score. The Random Forest model achieved an ROC AUC score of 0.8.., while the XGBoost model achieved a score of 0.8..... Feature importance and Mutual Information for the XGB model was also analyzed.

## 4. Project Setup

### File Structure

- **Data**: Contains the raw data files (however these won't be shared publically).
- **Code**: Contains Google Colab notebook.
- **Docs**: Houses documentation, including this README.
  
### Order of Code Execution

1. Data Preparation: Run data preprocessing scripts to clean and prepare data.
2. Data Exploration: Explore data using colab notebook.
3. Feature Engineering: Apply feature engineering techniques.
4. Modeling: Train Random Forest and XGBoost models using colab notebook.
5. Model Evaluation: Evaluate model performance and generate ROC curves.
6. Predictions: Make probability predictions for the test set.

### Features Used

- Demographic features: Feamle, Age_survey, Birthyear.
- Labor market features: Province, Geography, Status, Tenure, Schoolquintile, Round.
- Education-related features: Degree.

### Environment

- Cloud Environment: Google colaboratory using the Python 3.

### Expected Run Times

- Total expected time to run entire notebook = .... minutes

## Conclusion

In conclusion, this project effectively addressed the critical issue of youth unemployment in South Africa using machine learning. Two models, Random Forest Classifier and XGBoost Classifier, were developed and fine-tuned, achieving impressive ROC AUC scores of 0.8... and 0.8.., respectively. Notably, demographic features such as gender, along with other factors including province, geography, status, tenure, school quintile, round, age, and education level, played significant roles in determining youth employment outcomes. These insights provide a deeper understanding of the complex dynamics influencing youth employment outcomes and support evidence-based decision-making for organizations like Predictive Insights.

---
