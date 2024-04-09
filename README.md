# Marketing Strategy Analysis: Personalised Offer

## Overview

This repository contains a comprehensive analysis aimed at understanding the effectiveness of personalized offers in marketing strategies. Utilizing machine learning models, the project explores various factors influencing offer acceptance, such as demographics, offer details, and customer behavior.

## Data Loading

```python
import numpy as np 
import pandas as pd
import seaborn as sns
pd.options.display.max_columns = None
df = pd.read_csv('/kaggle/input/marketing-strategy-personalised-offer/train_data.csv')
df2 = pd.read_csv('/kaggle/input/marketing-strategy-personalised-offer/test_data.csv')
```

## Data Cleaning

Initial data cleaning steps include handling missing values, dropping irrelevant columns, and transforming categorical variables into numerical format for analysis.

## Data Visualization

Various visualization techniques are employed to understand the distribution and relationship between different features and offer acceptance. This includes bar plots, count plots, and cross-tabulation.

## Feature Engineering

Feature engineering is performed to create new features that better capture the underlying patterns in the data, improving the model's performance.

## Baseline Models

Several machine learning models, including Decision Tree, Bagging, Random Forest, AdaBoost, and Gradient Boosting classifiers, are trained as baseline models to predict offer acceptance.

## Hyperparameter Tuning

Hyperparameter tuning is conducted for Logistic Regression, SVC, and Gradient Boosting Classifier models to optimize their performance.

## Final Model Training

The best-performing models are retrained with the optimized parameters, and their performance is evaluated on the test set.

## Submission Generation

The final model predictions are prepared for submission to evaluate the model on unseen data.

## Citation

If you find this analysis useful, please cite the following:

```bibtex
@misc{e-commerce-shoppers-behaviour-understanding,
    author = {Your Name(s)},
    title = {Title of the Project},
    year = {Year},
    url = {URL to the Project or Kaggle Competition}
}

