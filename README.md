# Kaggle House Prices Competition

## Overview
This project is part of the Kaggle House Prices: Advanced Regression Techniques competition. It aims to predict the sale price of houses in Ames, Iowa, based on a comprehensive dataset of features. The goal is to build a model that accurately predicts the final price of each home, leveraging various regression techniques and data preprocessing methods.

## Dataset
The dataset includes 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. This competition challenges you to predict the final price of each home, with training and test sets provided. For more details, visit the [competition page](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

## Installation
To run this project, you'll need Python 3 and the following libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

You can install these packages using pip:
run `pip install -r requirements.txt` in your terminal.


## Files in the Repository
- `README.md`: This file provides an overview of the project and how to set it up and run it.
- `data/`: Directory containing the dataset and related files.
  - `data/data_description.txt`: Full description of each feature provided in the dataset.
  - `data/processed/`: Processed data files, including model submission files.
    - `data/processed/submission_baseline.csv`: Example of a submission file created from the baseline model.
  - `data/raw/`: Raw data files as downloaded from Kaggle.
    - `data/raw/test.csv`: Test set containing features without the sale prices.
    - `data/raw/train.csv`: Training set containing the features and target sale prices.
  - `data/sample_submission.csv`: A sample submission file in the correct format.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model development.
  - `notebooks/houses_kaggle_comp.ipynb`: Notebook containing the exploratory data analysis and initial modeling for the Kaggle competition.
- `requirements.txt`: A text file listing the project's dependencies required for reproducing the analysis environment.
- `src/`: Source code for the project's Python modules.
  - `src/__init__.py`: Makes Python treat the directories as containing packages.
  - `src/trainer/`: Modules related to model training.
    - `src/trainer/pipeline.py`: Defines the pipeline for data preprocessing and model training.
    - `src/trainer/preprocessors.py`: Contains custom preprocessing functions or classes.
    - `src/trainer/trainer.py`: Script for training the model, including model selection and evaluation.

## Model
StackingRegressor
-GradientBoostingRegressor
-Ridge
-SVR
-AdaBoostRegressor
-LinearRegression

## Results
Score: 0.12459
Rank: 500/3891

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

