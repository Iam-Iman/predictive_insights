# Predictive Insights - Youth Employment Project

## Project Overview

This documentation outlines the Predictive Insights project, which involved the development of two machine learning models using Random Forest Classifier and XGBoost Classifier. The objective was to predict youth employment based on data from labor market surveys in South Africa. This documentation follows the Team Data Science Process (TDSP) Lifecycle stages and provides insights into the project's scope, plan, personnel, metrics, data acquisition, understanding, modeling, and deployment.

## 1. Business Understanding

### Problem Definition

The primary goal of this project was to create predictive models for youth employment outcomes in South Africa using machine learning techniques. Two models, Random Forest Classifier and XGBoost Classifier, were developed to predict employment status based on demographic and labor market features.

### Scope

- Development of two binary classification models (Random Forest and XGBoost).
- Execution of the project in an Azure Machine Learning environment.
- Deployment of the final model using Azure Container Services.

### Plan

The project closely followed the TDSP lifecycle stages. It involved a data scientist and a technical program manager. Model performance was evaluated using ROC AUC score.

## 2. Data Acquisition and Understanding

### Raw Data

The dataset used for this project contained information from four rounds of a survey of youth in the South African labor market, conducted at 6-month intervals. The dataset included numerical, categorical, and free-form text responses, as well as demographic information such as age and education level.

### Data Exploration

Data exploration involved understanding the dataset's characteristics, distributions, and relationships between features. Key insights were derived using descriptive statistics and visualizations.

## 3. Modeling

### Feature Engineering

- Data preprocessing, including handling missing values and encoding categorical features.
- Standardization of numerical features.
- Saving processed datasets for model input.

### Modeling Training

Two machine learning models were trained: Random Forest Classifier and XGBoost Classifier. Hyperparameter tuning was conducted for both models to optimize their performance.

### Model Evaluation

Model performance was assessed using ROC AUC score. The Random Forest model achieved an ROC AUC score of 0.92, while the XGBoost model achieved a score of 0.90. Feature importance for the Random Forest model was also analyzed.

## 4. Deployment

### Architecture and Environment

- Development was carried out on an Azure Data Science Virtual Machine (DSVM).
- Azure Machine Learning and TDSP templates were used for project organization.
- Code execution occurred in the AMLW Python 3.5 environment using Azure Machine Learning CLI.

### Version Control Repository

Git was used for version control to track project changes and collaboration.

### Deployment

The Random Forest model was selected for deployment. Deployment was executed in Azure Container Services, which included Docker and Kubernetes for web service management.

### Code Execution

Code could be executed both locally and in the Azure Machine Learning environment, ensuring reproducibility and scalability.

## 5. Project Setup

### Folder Structure

- **Data**: Contains the raw and processed data files.
- **Code**: Contains Jupyter notebooks, Python scripts, and model files.
- **Docs**: Houses documentation, including this README.
- **Output**: Stores intermediate and final output files.
  
### Order of Code Execution

1. Data Preparation: Run data preprocessing scripts to clean and prepare data.
2. Data Exploration: Explore data using Jupyter notebooks.
3. Feature Engineering: Apply feature engineering techniques.
4. Modeling: Train Random Forest and XGBoost models using Jupyter notebooks.
5. Model Evaluation: Evaluate model performance and generate ROC curves.
6. Deployment: Deploy the chosen model for prediction.

### Features Used

- Demographic features: Gender, Age.
- Labor market features: Province, Geography, Status, Tenure, School Quintile, Round.
- Education-related features: Education Level.

### Environment

- Conda Environment: A conda environment.yml file is provided for replicating the Python environment used for this project.

### Hardware

- Development was done on an Azure Data Science Virtual Machine (DSVM) with specifications: DS3_V2, 4 virtual CPUs, 14GB RAM.

### Expected Run Times

- Data Preparation: 10 minutes
- Data Exploration: 20 minutes
- Feature Engineering: 15 minutes
- Modeling: 1 hour (each for Random Forest and XGBoost)
- Model Evaluation: 20 minutes
- Deployment: 30 minutes

## Conclusion

In conclusion, this project effectively addressed the critical issue of youth unemployment in South Africa using machine learning. Two models, Random Forest Classifier and XGBoost Classifier, were developed and fine-tuned, achieving impressive ROC AUC scores of 0.92 and 0.90, respectively. Notably, demographic features such as gender, along with other factors including province, geography, status, tenure, school quintile, round, age, and education level, played significant roles in determining youth employment outcomes. These insights provide a deeper understanding of the complex dynamics influencing youth employment outcomes and support evidence-based decision-making for organizations like Predictive Insights.

---
