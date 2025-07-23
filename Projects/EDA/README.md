# Project_EDA. Booking reviews

## Table of contents
[1. Project Description](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#project-description)

[2. What case we are solving?](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#what-case-we-are-solving)

[3. Short data information](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#short-data-information)

[4. Project work stage](__)

[5. Result](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#result)

[6. Conclusions](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#conclusions)

### Project Description
* One of the company's problems is dishonest hotels that inflate their ratings. One way to find such hotels is to build a model that predicts the hotel's rating. If the model's predictions differ greatly from the actual result, then the hotel may be cheating and should be checked. 
* Used instruments: Python: Cleaning data (Numpy, Pandas), Data visualisation (Seaborn, Matplot), Feature Engineering (OrdinalEncoder, LabelEncoder, OneHotEncoder, BinaryEncode,  MinMaxScaler) ML (Sklearn - RandomForestRegressor) 

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#table-of-contents)

### What case we are solving?
The project consist of 8 parts:

1. Cleaning data from missing values;

2. Feature engineering;

3. Encoding categorical features;

4. Analyzing text reviews;

5. Multicollinearity analysis;

6. Selecting features based on their importance;

7. Data scaling;

8. Implementing a machine learning algorithm.

**Competition conditions**


**Quality metric**
The results are assessed using the MAPE metric. Must be no more 13.5% 

**What we practice**
The main objective of the project was to learn the following skills:

* Data cleaning

* Data exploration (including quality of visualizations, generation of ideas, hypotheses, and providing comments)

* Feature generation

* Feature selection

* Feature transformation

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#table-of-contents)

### Short data information
Kaggle competition [Booking reviews](https://www.kaggle.com/competitions/sf-booking/data)


### Project work stage
1. Data introduction - we studied the data and identified gaps
2. Cleaning data from missing values - filled in the gaps in the longitude and latitude of the hotels
3. Feature engineering - created new features: "hotel country", "seasonality", "number of days of stay", "number of rooms", "type of trip", "type of guest"
4. Encoding categorical features - encoded all categorical features using OneHotEncoder, BinaryEncode and LabelEncoder
5. Analyzing text reviews - using SentimentIntensityAnalyzer we rated positive and negative reviews
6. Multicollinearity analysis - identified and removed multicolinear features
7. Selecting features - selected the most important features that influence the target variable
8. Data scaling - normalized features
9. ML - built and trained a RandomForestRegressor model on the training set and made a prediction on the test set

### Result
Result [here](https://github.com/Evgi23/dst_gigio/blob/main/Projects/EDA/EDA_project.ipynb)

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#table-of-contents)

### Conclusions

Processing textual features allowed us to improve the MAPE score from 14% to 12%. We also found that the features review_total_negative_word_counts and compound_positive_review have the greatest impact on hotel ratings. To further enhance the model's performance, additional work with text features is recommended.

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/tree/main/Projects/EDA#table-of-contents)
