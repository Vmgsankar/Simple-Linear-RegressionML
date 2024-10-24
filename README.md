# Simple Linear Regression Model

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Process](#modeling-process)
- [Results](#results)

## Overview
This project demonstrates the implementation of a **Simple Linear Regression** model to predict employee salary based on years of experience. The dataset used contains two features: `YearsExperience` and `Salary`.

## Dataset
The dataset used for this project is `Salary_Data.csv`, which consists of the following columns:
- `YearsExperience`: Number of years of experience an employee has.
- `Salary`: Corresponding salary of the employee.

## Dependencies
- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## Installation
1. Clone the repository:
   ```bash
   git clone https:https://github.com/Vmgsankar/Simple-Linear-RegressionML
   ```
2. Navigate to the project directory:
   ```bash
   cd Simple-Linear-RegressionML
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
The project can be used to:
- Analyze the relationship between years of experience and salary
- Predict salaries for given years of experience
- Understand basic linear regression implementation
- Visualize salary trends based on experience

## Modeling Process
1. **Data Preprocessing**
   - Data loading and inspection
   - Handling missing values
   - Feature scaling if required
   - Train-test split (80-20 ratio)

2. **Model Development**
   - Linear regression model initialization
   - Model training using training data
   - Prediction on test data
   - Model evaluation and validation

3. **Visualization**
   - Scatter plots of actual vs predicted values
   - Regression line visualization
   - Residual analysis plots

## Results
- Model Performance Metrics:
  - R-squared (R²) score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
- Visual representation of predictions
- Analysis of model accuracy and limitations
