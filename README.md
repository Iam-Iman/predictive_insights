# Predictive Insights Youth Employment

## Overview

This data science project aims to address the critical issue of youth unemployment in South Africa by developing predictive models using machine learning techniques. The project leverages data from labor market surveys conducted over four rounds at six-month intervals. The primary objective is to predict whether a young person will be employed one year after the baseline survey.

The project utilizes two primary machine learning models, namely the RandomForestClassifier and XGBoost, with a focus on optimizing the XGBoost model's hyperparameters using GridSearchCV. The ultimate goal is to achieve a high ROC AUC score, demonstrating the model's effectiveness in predicting youth employment outcomes.

## Data

- The dataset consists of information collected at the baseline survey, including numerical, categorical, and text responses.
- Additional demographic information such as age, school level, and results are included.
- The training set comprises one observation per individual, containing baseline information and the target outcome (employed or not) one year later.
- The test set includes baseline data without the target outcome.

## Key Findings

- The optimized XGBoost model achieved a significant ROC AUC score of 0.8584, showcasing its predictive power.
- Demographic features like gender, province, geography, status, tenure, schoolquintile, round, age, and education level played a substantial role in determining youth employment outcomes.
- Notably, school subjects had a limited impact on employment probabilities, while education levels such as matriculation and degrees emerged as influential factors.

## Repository Structure

- `data/`: Contains the dataset used in the project.
- `notebooks/`: Jupyter notebooks detailing data exploration, preprocessing, model training, and evaluation.
- `src/`: Source code for custom functions or modules.
- `requirements.txt`: Lists all project dependencies for reproducibility.


## Conclusion

This project underscores the potential of machine learning and data-driven solutions in addressing pressing societal challenges like youth unemployment. The achieved ROC AUC score of 0.8584 reflects the model's accuracy and its ability to provide valuable insights for informed decision-making and interventions.

By understanding the complex dynamics of youth employment outcomes, this project contributes to economic empowerment and supports the career growth of young individuals in South Africa.

## Contributors

- [Iman Ngwepe-Ntshibida](https://github.com/Iam-Iman)

## License

This project is licensed under the [MIT License](LICENSE).
