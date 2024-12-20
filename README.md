# SageMaker Random Forest Classification Project

## Overview

This project demonstrates the use of **Amazon SageMaker** to build, train, and deploy a machine learning model using the Random Forest classifier from the **scikit-learn** library. The tutorial is designed for understanding the process of developing custom machine learning scripts, managing data pipelines, and running jobs in the SageMaker environment.

---

## Key Features

- **Custom Training Script**: The project includes a Python script (`script.py`) that handles model training, evaluation, and saving.
- **Data Handling**: Reads training and testing datasets in CSV format and splits them into features and labels.
- **Hyperparameter Tuning**: Allows customization of `n_estimators` and `random_state` via command-line arguments.
- **Model Persistence**: Saves the trained model as a `.joblib` file in the specified model directory for later inference.
- **Evaluation Metrics**: Provides metrics such as accuracy, precision, recall, and F1-score on the test data.

---

## Files

1. **`script.py`**: The main Python script for training the Random Forest model.
2. **`Tutorial - 1 Sagemaker SKlearn Custom Script.ipynb`**: A Jupyter Notebook to guide you through the process of setting up and running the project in SageMaker.

---

## Requirements

- **Environment**:
  - Python 3.8+
  - SageMaker environment with access to S3 bucket.
- **Libraries**:
  - `scikit-learn`
  - `joblib`
  - `boto3`
  - `pandas`
  - `numpy`

---

## License

This project is licensed under the MIT License. Feel free to use and modify it for your purposes.

