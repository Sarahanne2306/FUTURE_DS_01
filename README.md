# Titanic Dataset Survival Prediction Analysis

This project analyzes the Titanic dataset to predict passenger survival based on various features such as age, gender, passenger class, and more. Through data cleaning, exploratory analysis, and predictive modeling, the project uncovers insights into survival patterns and builds a logistic regression model to predict survival outcomes.


## Project Overview


The goal of this analysis is to explore survival factors, visualize passenger demographics, and predict survival using machine learning. 
Key insights are derived from exploratory data analysis (EDA), and a logistic regression model is used to evaluate survival predictions.

## Steps Involved

### Data Cleaning:

Imputed missing values in the Age column based on passenger class.

Removed columns with excessive missing values (e.g., Cabin).

Dropped rows with missing values and converted categorical features into dummy variables.


### Exploratory Data Analysis (EDA):

Visualized survival rates by gender and passenger class.

Analyzed the distribution of ages and fares.

Investigated sibling/spouse counts to understand family travel patterns.


### Predictive Modeling:

Used logistic regression for binary classification (survived or not).

Evaluated model performance using accuracy, precision, recall, and F1 score.

Achieved an accuracy of approximately 80%.


## Key Findings
Gender and Class: Higher survival rates among female passengers and those in first class.

Age Groups: Younger passengers tended to have higher survival rates.

Family Size: Family presence (siblings or spouse) influenced survival odds.


## Libraries Used
Pandas, NumPy: Data manipulation and cleaning

Seaborn, Matplotlib: Data visualization

Scikit-Learn: Model building and evaluation
