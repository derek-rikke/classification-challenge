# classification-challenge
Module 13 Challenge

# Spam Detector

## Overview
This project demonstrates the application of machine learning techniques to classify emails as spam or not spam. It uses Python's pandas library for data manipulation and scikit-learn for model training and evaluation, utilizing a dataset from the UCI Machine Learning Repository.

## Dataset
The dataset, sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/spambase), can be directly accessed [here](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv). It comprises various features extracted from emails, labeled as spam or not spam.

## Prerequisites
- Python 3.x
- pandas
- scikit-learn

## Installation
Ensure Python 3.x is installed on your system, then install the required libraries using pip:

\```bash
pip install pandas scikit-learn
\```

## Usage
Follow these steps to execute the project:

1. **Data Retrieval**: Download the dataset from the provided link and use pandas to import it.
2. **Preprocessing**:
    - Split the data into features (X) and target labels (y).
    - Use `train_test_split` to divide the data into training and testing sets.
    - Scale the features using `StandardScaler`.
3. **Model Training**:
    - Train a Logistic Regression model and a Random Forest Classifier.
4. **Evaluation**: Evaluate and compare the accuracy of both models on the test data.

## Code Structure
- Import necessary libraries.
- Load and display the dataset.
- Discuss predictions on model performance.
- Preprocess the data by splitting and scaling.
- Train Logistic Regression and Random Forest Classifier models.
- Evaluate and compare model performances.

## Results
The accuracy of each model is discussed, and an evaluation is made on whether the initial prediction about the model performance was accurate.

## Conclusion
The findings, including which model performed better and potential reasons for this performance, are summarized.

## License
This project is released under the MIT License.
