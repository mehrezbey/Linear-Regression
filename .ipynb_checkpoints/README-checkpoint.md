# Linear-Regression

This repository contains various implementations of linear regression models, including univariate and multivariate linear regression. It also explores the impact of feature scaling on model performance and demonstrates feature engineering techniques using polynomial regression.

## Repository Structure

- `data/`
  - `train_univariate.csv`: Dataset for univariate linear regression.
  - `train_multi.csv`: Dataset for multivariate linear regression, containing student performance indices based on factors such as hours of study, sleep, previous scores, etc.

- `univariate_linear_regression.ipynb`: Implementation of univariate linear regression from scratch, including gradient descent, cost calculation, evaluation, and prediction.

- `multiple_linear_regression.ipynb`: Implementation of multivariate linear regression from scratch. This notebook includes:
  - Gradient descent optimization.
  - Error calculation.
  - Range checking and feature scaling to demonstrate the impact on model speed, performance, and accuracy.

- `multiple_linear_regression_with_sklearn.ipynb`: Solving the same multivariate linear regression problem using the scikit-learn library for comparison.

- `feature_engineering.ipynb`: Demonstration of feature engineering techniques, including polynomial regression, to model more complex functions using features such as \(x^2\) and \(x^3\).

## Notebooks Overview

### 1. Univariate Linear Regression

- **File**: `univariate_linear_regression.ipynb`
- **Description**: 
  - Implements univariate linear regression from scratch.
  - Uses gradient descent for optimization.
  - Includes cost function calculation, model evaluation, and prediction.

### 2. Multivariate Linear Regression (from scratch)

- **File**: `multiple_linear_regression.ipynb`
- **Description**:
  - Implements multivariate linear regression from scratch.
  - Optimizes using gradient descent.
  - Includes comprehensive error calculation and data cleaning steps.
  - Demonstrates the importance of feature scaling and its impact on the model's speed, performance, and accuracy.

### 3. Multivariate Linear Regression (using scikit-learn)

- **File**: `multiple_linear_regression_with_sklearn.ipynb`
- **Description**:
  - Solves the multivariate linear regression problem using the scikit-learn library.
  - Provides a comparison with the from-scratch implementation.

### 4. Feature Engineering with Polynomial Regression

- **File**: `feature_engineering.ipynb`
- **Description**:
  - Explores feature engineering techniques.
  - Implements polynomial regression to model complex functions.
  - Transforms features to \(x^2\), \(x^3\), etc., to improve model accuracy.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries:

  ```bash
  pip install numpy pandas matplotlib scikit-learn
  ```
  

### Running the Notebooks

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/Linear-Regression.git
    cd Linear-Regression
    ```
2. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3. Open and run the desired notebook from the Jupyter interface.

## Acknowledgments
This repository is inspired by Coursera s' Supervised Machine Learning Course.
Datasets used are synthetic or adapted for demonstration purposes.