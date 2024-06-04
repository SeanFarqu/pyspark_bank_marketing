# Bank Marketing Campaign Analysis

This project uses PySpark to analyze a bank marketing campaign dataset. The goal is to evaluate different aspects of the campaign, including contact methods and their effectiveness, using machine learning models and A/B testing. The dataset used for this analysis is the "Bank Marketing" dataset from the UCI Machine Learning Repository.

## Project Overview

This project includes the following key components:

1. **Data Loading and Cleaning**:
   - Load the bank marketing dataset.
   - Clean the dataset by handling missing values and correcting data types.

2. **Feature Engineering**:
   - Create new features such as `is_married` and `has_loan`.
   - Encode categorical variables.

3. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of features.
   - Analyze the correlation between features.

4. **Machine Learning Model**:
   - Train a Logistic Regression model to predict whether a customer will subscribe to a term deposit.
   - Evaluate the model using accuracy and F1 score.

5. **A/B Testing**:
   - Divide the dataset into two groups based on the contact method (cellular vs. telephone).
   - Calculate and compare conversion rates for both groups.

## Dataset

The dataset used in this project is the "Bank Marketing" dataset from the UCI Machine Learning Repository. It contains information about direct marketing campaigns (phone calls) of a Portuguese banking institution.

## Getting Started

### Prerequisites

- Apache Spark
- PySpark
- Python 3.x
- Pandas
- Seaborn
- Matplotlib
