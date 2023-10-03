# Predictive Insights Youth Employment Project

## Project Overview

This data science project focuses on addressing youth unemployment in South Africa by developing predictive models using machine learning techniques. The project aims to predict youth employment outcomes based on data collected from labor market surveys. This README file provides comprehensive information on setting up the project, running the code, understanding features, environment setup, hardware requirements, and expected run times for each notebook.

## Folder Structure

The project follows the following folder structure:

```
predictive_insights/
├── data/
│   ├── raw_data.csv          # Raw dataset
│   ├── processed_data.csv    # Processed dataset
├── notebooks/
│   ├── 01_data_preparation.ipynb   # Data preprocessing
│   ├── 02_feature_engineering.ipynb  # Feature engineering
│   ├── 03_model_training.ipynb      # Model training and evaluation
│   └── 04_results_visualization.ipynb  # Results visualization
├── src/
│   ├── utils.py        # Custom utility functions
├── requirements.txt    # List of project dependencies
├── environment.yml     # Conda environment file
└── README.md           # Project documentation
```

## Order of Execution

1. Start with `01_data_preparation.ipynb` to perform data preprocessing, cleaning, and exploration.
2. Move on to `02_feature_engineering.ipynb` for feature engineering and data transformation.
3. Proceed with `03_model_training.ipynb` to train and evaluate machine learning models.
4. Finally, explore the results and visualizations in `04_results_visualization.ipynb`.

## Features Explanation

- **Gender:** Categorical feature representing the individual's gender.
- **Province:** Categorical feature indicating the individual's province.
- **Geography:** Categorical feature describing the geographical region.
- **Status:** Categorical feature representing the individual's employment status.
- **Tenure:** Numerical feature indicating the duration of employment.
- **Schoolquintile:** Categorical feature representing the school quintile.
- **Round:** Categorical feature denoting the survey round.
- **Age:** Numerical feature indicating the individual's age.
- **Education Level:** Categorical feature representing the highest education level attained.

## Environment Setup

To replicate the project environment, you can use the provided Conda environment file:

- `environment.yml`: Create a Conda environment using this file.

```bash
conda env create -f environment.yml
conda activate predictive-insights-env
```

You can also install the required dependencies using pip:

- `requirements.txt`: Install dependencies using pip.

```bash
pip install -r requirements.txt
```

## Hardware Requirements

This project can be run on a standard laptop or a machine with the following specifications:

- CPU: Dual-core processor or higher
- RAM: 8GB or more
- Disk Space: 1GB free space for data and code
- Operating System: Windows, macOS, or Linux

The platform used was cloud-based, Google Colab connected to Python 3 Google Compute Engine backend.

## Expected Run Time Of The Entire Notebook

- `predictive_insights_notebook.ipynb`: Approximately 8.6 minutes

The run times may vary based on system used.

## Contributors

- [Iman Ngwepe-Ntshibida](https://github.com/Iam-Iman)

## License

This project is licensed under the [MIT License](LICENSE).

---

