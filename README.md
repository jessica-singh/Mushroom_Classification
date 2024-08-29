# Mushroom Classification Project

## Overview

This project focuses on classifying mushrooms using machine learning techniques. The goal is to predict whether a mushroom is edible or poisonous based on various features. The project involves data preprocessing, model training, hyperparameter tuning, and performance evaluation.

## Key Features

- **Data Preprocessing:** Categorical features are encoded using `CatBoostEncoder` to convert categorical variables into numerical values.
- **Modeling:** XGBoost is employed for classification due to its efficiency and performance.
- **Optimization:** Optuna is used for hyperparameter tuning to find the best model parameters.
- **Performance:** Achieved a final model accuracy of **99.00%** on the test dataset.

## Project Structure

- `mush.ipynb`: Jupyter Notebook containing the project code and analysis.
- `test.zip`: ZIP file containing the test dataset. (Note: You may need to extract this ZIP file to access the data.)
- `train.csv`: CSV file with training data used for model training. (Ensure this file is correctly formatted and available in your working directory.)

## Installation

To run this project locally, you need to have Python installed along with the following libraries:

- `xgboost`
- `optuna`
- `scikit-learn`
- `pandas`
- `numpy`
- `category_encoders`

You can install the required packages using pip:

```bash
pip install xgboost optuna scikit-learn pandas numpy category_encoders
