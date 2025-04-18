# STML2 Project Homework 1

# Youth Drug Use Prediction Using Decision Trees (NSDUH 2023)
This project investigates patterns of substance use among youth under the age of 18 using the 2023 National Survey on Drug Use and Health (NSDUH) dataset. The objective is to build interpretable machine learning models that can help identify key behavioral, emotional, and demographic factors associated with the use of alcohol, marijuana, and cigarettes.

## Objectives
•	Predict youth drug use behavior using decision tree-based models.
•	Identify significant predictors of substance use, including emotional and social factors.
•	Provide interpretable insights to support early intervention and policy recommendations.

## Models Implemented
•	Binary Classification: Predict whether a youth has ever used cigarettes (CIG_USED)
•	Multi-class Classification: Classify marijuana use frequency categories (IRMJFM)
•	Regression: Estimate the number of days alcohol was consumed in the past year (ALCYDAYS)

## Tools and Techniques
•	Programming Language: Python
•	Libraries: pandas, scikit-learn, matplotlib
•	Models: Decision Tree, Random Forest, Linear Regression
•	Evaluation Metrics: Accuracy, F1 Score, Mean Squared Error (MSE), R-squared (R²)

## Key Findings
•	Emotional stress (SCHFELT) consistently emerged as the most influential predictor across all models.
•	Additional predictors include gender, household income, and peer influence variables.
•	While decision tree models provided useful interpretability, they showed signs of overfitting, particularly on training data.

## Limitations and Future Work
•	Class imbalance affected the performance of classification models.
•	A single train-test split was used; cross-validation should be incorporated for more reliable evaluation.
•	Only a small subset of available variables was used. Future versions should include broader factors such as parental involvement and mental health indicators.
•	Enhancements like ensemble modeling and feature selection methods can be added to improve robustness and generalizability.

## Project Deliverables
•	Preprocessed and labeled dataset
•	Complete Jupyter Notebook with data cleaning, modeling, and evaluation
•	Script covering project methodology, results, and ethical implications
