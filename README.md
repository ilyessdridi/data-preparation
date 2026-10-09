# Data Preparation for Machine Learning

A hands-on Jupyter Notebook exploring the essential techniques of **data preprocessing for machine learning** using Python, Pandas, NumPy, and Scikit-learn.

## Project Overview

This project demonstrates how to prepare raw datasets before applying machine learning algorithms.

It covers creating and exploring DataFrames, handling missing values, selecting relevant features, encoding categorical variables, scaling numerical data, and introducing dimensionality reduction.

## Topics Covered

### 1. Data Manipulation and Exploration
- Creating DataFrames using Pandas Series and dictionaries
- Loading CSV and Excel datasets
- Inspecting data using `head()`, `tail()`, `info()`, and `describe()`

### 2. Data Cleaning
- Detecting missing values with `isnull()` and `isna()`
- Mean imputation
- Median imputation
- Mode imputation

### 3. Feature Selection
- Selecting relevant features using `SelectKBest`
- Applying the Chi-squared statistical test
- Feature selection using the Pima Indians Diabetes dataset

### 4. Categorical Data Encoding
- Ordinal encoding for ordered categories
- One-hot encoding for nominal categories
- Understanding categorical-to-numerical transformations

### 5. Feature Scaling
- Standardization using `StandardScaler`
- Min-Max normalization concepts and examples
- Understanding when and why scaling matters

### 6. Dimensionality Reduction
- Introduction to Principal Component Analysis (PCA)
- Covariance matrices
- Eigenvalues and eigenvectors
- Projection onto principal components

**Note:** The PCA section contains exercises that are not yet fully implemented, and the Min-Max examples are currently commented out.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Datasets

The notebook uses:
- Student data created with Pandas
- Horse Colic dataset
- Titanic dataset
- Pima Indians Diabetes dataset
- Local Excel data

The Titanic CSV and Excel files need to be supplied locally. The Horse Colic and Diabetes datasets are loaded from public URLs.

## Installation

Install the required libraries:

`pip install numpy pandas matplotlib scikit-learn openpyxl notebook`

Launch Jupyter:

`jupyter notebook`

Open `DataPreparation.ipynb` and follow the sections in order.

Some cells may require indentation fixes or additional data files before they can execute successfully.

## Learning Outcomes

By completing the exercises, you will understand how to:

- Prepare datasets for machine learning
- Clean and explore structured data
- Handle missing information
- Select useful input variables
- Convert categorical features to numerical representations
- Apply feature scaling techniques
- Understand the fundamentals of PCA

## Project Status

Educational notebook covering the fundamental stages of data preparation. Some exercises remain incomplete.

---

**Python | Data Science | Machine Learning | Data Preprocessing**
