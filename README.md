# Titanic Survival Prediction with Random Forest

This repository contains a Python script for predicting the survival of passengers on the Titanic using a Random Forest classifier. The script performs data preprocessing, analysis, visualization, and model training on the Titanic dataset.

## Table of Contents
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis and Visualization](#analysis-and-visualization)
- [Model Training and Evaluation](#model-training-and-evaluation)


## Dataset
The dataset used in this project is the Titanic dataset, which is available on [Kaggle](https://www.kaggle.com/c/titanic/data). It includes the following features:
- PassengerId
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked
- Survived (target variable, 1 indicates survived, 0 indicates did not survive)

## Installation
To run this project, you need to have Python and the following libraries installed:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using the following command:
```
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/titanic-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd titanic-prediction
    ```
3. Run the script:
    ```bash
    python titanic_analysis.py
    ```

## Analysis and Visualization
The script performs the following data analysis and visualization tasks:
- Displays dataset information and summary statistics.
- Checks for missing values and handles them appropriately.
- Generates various plots to visualize data distributions and relationships:
  - Histograms
  - Box plots
  - Bar plots

## Model Training and Evaluation
The script trains a Random Forest classifier using the following steps:
1. Preprocesses the data (handling missing values, encoding categorical variables, etc.).
2. Splits the data into training and testing sets.
3. Fits a Random Forest model to the training data.
4. Predicts survival on the test data.
5. Evaluates the model using a confusion matrix and classification report.
