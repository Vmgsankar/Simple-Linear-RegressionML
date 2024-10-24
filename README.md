
# Simple Linear Regression Model

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Process](#modeling-process)
- [Results](#results)
- [License](#license)

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

You can install the required dependencies by running:
```bash
pip install -r requirements.txt
```

## Installation
1. Clone the repository:
   ```bash
   git clone https:https://github.com/Vmgsankar/Simple-Linear-RegressionML
   ```
2. Navigate to the project directory:
   ```bash
   cd Simple-Linear-RegressionML
   ```

## Usage
1. Load the dataset:
   ```python
   df_sal = pd.read_csv('Salary_Data.csv')
   df_sal.head()
   ```
2. Train a simple linear regression model using `scikit-learn`:
   ```python
   from sklearn.model_selection import train_test_split
   from sklearn.linear_model import LinearRegression

   X = df_sal[['YearsExperience']]
   y = df_sal['Salary']

   X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

   model = LinearRegression()
   model.fit(X_train, y_train)
   ```
