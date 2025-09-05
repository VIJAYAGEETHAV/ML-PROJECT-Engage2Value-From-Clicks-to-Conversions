# ML-PROJECT--🎯 Engage2Value: From Clicks to Conversions

A Machine Learning project developed for the Kaggle competition Engage2Value: From Clicks to Conversions, aimed at predicting customer purchase values based on multi-session digital behavior.

📌 Project Overview

This project focuses on estimating a customer’s purchase value by analyzing anonymized behavioral data collected across multiple digital touchpoints.

The dataset includes:

Browser types

Traffic sources

Device details

Geographic information

The objective is to build models that can capture behavioral patterns and predict purchase potential, ultimately helping businesses optimize marketing strategies and improve customer engagement.

🎯 Objective

To build and optimize machine learning models that:

Predict purchase value for each customer session.

Perform well on unseen test data.

Generate valid Kaggle submissions in the required format.

Contribute to data-driven decision-making in digital marketing.

🧠 Methodology
1. Data Preprocessing

Handled missing values through imputation strategies.

Applied scaling and encoding techniques for numerical and categorical features.

Reduced dimensionality using Truncated SVD and selected informative features.

2. Exploratory Data Analysis (EDA)

Analyzed patterns in multi-session interactions.

Examined correlations between clicks, page views, and conversions.

Identified redundant or constant features and removed noise.

3. Modeling & Evaluation

Baseline models: Linear Regression, SGD Regressor.

Advanced models: Random Forest Regressor, Gradient Boosting.

Hyperparameter tuning for improved accuracy.

Evaluation metric: R² score.

4. Submission Workflow

Predictions stored in a DataFrame with columns id and purchaseValue.

Exported results to CSV following the format:

id,purchaseValue
0,0
1,0
2,10990000
3,36500
...

🧰 Technologies & Tools

Languages: Python

Libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn, xgboost

Environment: Jupyter Notebook

Version Control: Git & GitHub

Platform: Kaggle

📊 Results

Successfully implemented baseline and advanced models.

Achieved strong local R² scores during experimentation.

Built reusable pipelines for preprocessing, feature selection, and modeling.
