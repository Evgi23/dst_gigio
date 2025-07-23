# Project_4. Predicting deposit openings

## Table of contents
[1. Project Description](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#project-description)

[2. What case we are solving?](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#what-case-we-are-solving)

[3. Short data information](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#short-data-information)

[4. Project work stage](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#project-work-stage)

[5. Result](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#result)

[6. Conclusions](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#conclusions)

### Project Description
* This project aims to develop a machine learning model capable of predicting whether a bank client will subscribe to a term deposit. The analysis is based on historical data from a marketing campaign carried out by a bank, with the ultimate goal of improving campaign targeting and increasing deposit conversion rates.  
* Python: Cleaning data (Numpy, Pandas), Data visualization (Seaborn, Matplot), Feature Engineering (OrdinalEncoder, LabelEncoder, OneHotEncoder, BinaryEncode, SelectKBest,  MinMaxScaler) ML (Sklearn - LogisticRegression, DecisionTreeClassifier, GridSearchCV, RandomForestClassifier, GradientBoostingClassifier, StackingClassifier)

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#table-of-contents)

### What case we are solving?
The project consist of 5 parts:

1. Part 1. Data exploration, handling missing values and outliers;

2. Part 2:  Exploratory Data Analysis;

3. Part 3: Feature Engineering;

4. Part 4: Solving a Classification Problem: Logistic Regression and Decision Trees;

5. Part 5: Solving a Classification Problem: Model Ensembles and Making Predictions.



**Competition conditions**


**Quality metric**
Model performance is assessed using key evaluation metrics, including accuracy, precision, recall, and the F1-score

**What we practice**
The main objective of the project was to learn the following skills:

* Data cleaning

* Data exploration (including quality of visualizations, generation of ideas, hypotheses, and providing comments)

* Feature generation

* Feature selection

* Feature transformation

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#table-of-contents)

### Short data information

This is real data collected from one of the top banks in the country

### Project work stage
* Part 1 Initial Data Processing - In this step, we handled missing values and removed outliers to ensure the data was clean and ready for analysis
* Part 2 Exploratory Data Analysis (EDA)- We explored the dataset to uncover early patterns and generate initial hypotheses about the relationships between features and the target variable
* Part 3 Feature Selection and Transformation - At this stage, we encoded and transformed the data into a suitable format for solving a classification problem
* Part 4 Classification: Logistic Regression and Decision Trees - We built our first predictive models using logistic regression and decision trees, evaluated their performance, and tuned model parameters to achieve better results for each algorithm
* Part 5 Classification: Model Ensembles and Final Prediction - In the final stage, we enhanced prediction quality by applying more advanced ensemble methods. We then assessed which model provided the most accurate and reliable forecasts


### Result
Result [here](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/Project_4_ML_eng.ipynb)

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#table-of-contents)

### Conclusions
The machine learning models were developed to solve the classification task. Their performance on the test dataset is summarized below
* LogisticRegression accuracy: 0.81, f1_score: 0.78
* DecisionTreeClassifier accuracy: 0.75, f1_score: 0.73
* DecisionTreeClassifier(max_depth = 6): accuracy: 0.75, f1_score: 0.73
* Using GridSearchCV, we determined that the optimal hyperparameters for the DecisionTreeClassifier model are: max_depth = 5 and min_samples_leaf = 7.
* random forest: accuracy of test data - 0.83
* gradient boosting: accuracy of test data - 0.83
* StackingClassifier, which achieved the following results::  accuracy: 0.82, f1-score: 0.81
* optuna RandomForestClassifier accuracy : 0.83 f1_score: 0.82

The best results were achieved by the RandomForestClassifier model with hyperparameter optimization using Optuna: accuracy : 0.83 f1_score: 0.82


:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/Projects/ML/README.md#table-of-contents)
