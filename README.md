# Multiple Linear Regression

## Overview

This project demonstrates the implementation of Multiple Linear Regression using Python and the scikit-learn library. Multiple Linear Regression is a machine learning algorithm used for predicting a dependent variable based on multiple independent variables.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Description

The project uses a dataset (`50_Startups.csv`) to predict the profit of startups based on multiple features, including R&D Spend, Administration Spend, Marketing Spend, and the State of operation. The key steps of the project are as follows:

1. **Importing Libraries:** Numpy, Matplotlib, and Pandas are imported for data manipulation and visualization.

2. **Importing Dataset:** The dataset is loaded and separated into independent variables (`X`) and the dependent variable (`y`).

3. **Encoding Categorical Data:** Categorical data (State) is encoded using One-Hot Encoding to allow the model to work with non-numeric features.

4. **Splitting Dataset:** The dataset is split into training and test sets using `train_test_split` from scikit-learn.

5. **Training Model:** The Multiple Linear Regression model is trained on the training set using scikit-learn's `LinearRegression`.

6. **Predictions:** The model predicts the profits on the test set, and the results are printed.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/repoabhi-git/multiple-linear-regression.git
Install the required libraries:

bash
Copy code
pip install numpy matplotlib pandas scikit-learn
Run the Python script:

bash
Copy code
python multiple_linear_regression.py
Usage
Modify the script as needed or use it as a template for your own Multiple Linear Regression tasks. Ensure that you have a dataset in the same format as 50_Startups.csv for training and testing.

## Results
The project prints the predicted profits and actual profits for the test set, allowing you to evaluate the performance of the Multiple Linear Regression model.
