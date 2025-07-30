# Project_6. Customer segmentation for an online gift shop

## Table of contents
[1. Project Description](https://github.com/Evgi23/dst_gigio/blob/main/README.md#project-description)

[2. What case we are solving?](https://github.com/Evgi23/dst_gigio/blob/main/README.md#what-case-we-are-solving)

[3. Short data information](https://github.com/Evgi23/dst_gigio/blob/main/README.md#short-data-information)

[4. Project work stage](__)

[5. Result](https://github.com/Evgi23/dst_gigio/blob/main/README.md#result)

[6. Conclusions](https://github.com/Evgi23/dst_gigio/blob/main/README.md#conclusions)

### Project Description
* This project focuses on customer segmentation for a UK-based online retail company using real transactional data from 2010–2011. The goal is to cluster customers based on their purchasing behavior (recency, frequency, and monetary value) and define targeted engagement strategies. The workflow includes data preprocessing, exploratory analysis, feature engineering, and the development of machine learning models for clustering and behavior prediction.  
* Python: Cleaning data (Numpy, Pandas), Data visualization (Seaborn, Matplot, Ploty), Feature Engineering (OrdinalEncoder, LabelEncoder, OneHotEncoder, BinaryEncode, SelectKBest, Pipeline, PCA, StandardScaler MinMaxScaler) ML (Sklearn - KMeans, DBSCAN, AgglomerativeClustering)

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/README.md#table-of-contents)

### What case we are solving?
The project consist of 5 parts:

1. Part 1. Exploring the structure of the dataset;

2. Part 2:  Data Transformation, Cleaning, and Analysis:
    2.1 Transaction Data Cleaning and Transformation
        2.1.1. Missing Values
        2.1.2. Duplicates
        2.1.3. Transactions with Negative Item Quantities
        2.1.4. Specialized Transactions
        2.1.5. Transactions with Items of Zero Cost
        2.1.6. Total price
    2.2. Exploratory Data Analysis (EDA)
    2.3. Building the RFM table and detecting RFM outliers;

3. Part 3: Building the Model and Evaluating Its Performance
    3.1. Clustering Based on RFM Features
    3.2. Interpretation of Clustering Results
        3.2.1. Cluster Visualization
        3.2.2. Building Cluster Profiles;

4. Part 4: Conclusions



**Competition conditions**


**Quality metric**
Visual Representation of the Clusters

**What we practice**
The main objective of the project was to learn the following skills:

* Data cleaning

* Data exploration (including quality of visualizations, generation of ideas, hypotheses, and providing comments)

* Feature generation

* Feature selection

* Feature transformation

* ML clustering

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/README.md#table-of-contents)

### Short data information

However,[The UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php)  create a dataset containing actual transactions from 2010 and 2011 was created, and this is the one we’ll be working with in this case study

### Project work stage
* Part 1 Exploring the structure of the dataset - we explored the structure and content of the dataset and performed basic preprocessing by conducting a statistical overview of numeric features, identifying the number of unique customers, determining the countries involved in transactions, checking for missing values and duplicates, and converting columns into appropriate formats such as datetime.
* Part 2 Data Transformation, Cleaning, and Analysis - We cleaned the missing values, removed the duplicates, processed negative and specialized transactions, create new features and processed EDA.
* Part 3 Building the Model and Evaluating Its Performance - At this stage, we build 3 clustering models and make plots of clusters. 
* Part 4 Conclusions



### Result
Result [here](https://github.com/Evgi23/dst_gigio/blob/main/Project-1.ipynb)

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/README.md#table-of-contents)

### Conclusions
**In this project, we analyzed customer data from an online gift store and built clustering models.
Two models produced the most effective segmentation results, allowing us to identify the following customer segments.**

The KMeans clustering identified three customer groups:

* Cluster 1: customers with the longest time since their last purchase.

* Cluster 2: customers with a high number of purchases and above-average spending, with a moderate recency level.

* Cluster 3: customers with the highest purchase frequency and the largest monetary value.

The AgglomerativeClustering algorithm identified two clusters:

* Cluster 1: customers with the longest time since their last purchase.

* Cluster 2: customers with the highest spending and purchase frequency.





:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/README.md#table-of-contents)