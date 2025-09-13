# Predicting Credit Card Approval With Using Python

This machine learning project mainly focuses on predicting one's approval for a credit card application based on their demmographics and financial status. 
---

### Problem Overview

Credit card issuers often receive high volume of applications. Additionally, manual evaluation may be time consuming and inconsistent. With that being said, by buiding a predictive model via machine learning, this aids bank in improving their efficiency and removing human biasness. 

---

### Dataset 

The data was obtained in Kaggle consisting of two datasets, with one CSV file including all important attritbutes such as gender, marital status, nnumber of children, annual income, whereas the other CSV file contains their approval status, with "1" being approved and "0" being rejected. 

### Data Preprocessing 

In order to obtain accurate results, data cleaning was done. It was found that there were no duplicates. Moving on, the two CSV files were merged via "left join" with using Individual ID as the key variable. It was also observed that there were missing values in columns such as Types of Occupation, Gender and Birthday Count.Since the Type of Occupation column contained a substantial number of missing values (488) compared to Gender (23) and Birthday Count (22), and was not deemed highly important for the analysis, it was removed from the dataset. Other missing values were removed following this. 


### Explanatory Data Analysis

Following the data cleaning process, an exploratory data analysis (EDA) was conducted to better understand the structure and characteristics of the dataset. Summary statistics and visualizations were used to examine distributions, detect outliers, and identify potential relationships between variables.

For the categorical variables, bar charts were utilized to highlight the distribution of categories such as Gender whereas for the numerical variables, descriptive statistics (mean, median, standard deviation). Visualizations including histograms and boxplots were applied to assess central tendencies, variability, and the presence of skewness or extreme values.

In addition, bivariate analyses were performed to explore potential correlations and patterns between variables. Scatter plots and correlation heatmaps provided insights into the strength and direction of relationships among numerical features. It was found that there is a high  positive correlation between the Number of Children and Number of Family Members. Additionally, a strong negative correlation was observed between Birthday Count and Employed days. Hence, Number of Family Members and Birthday Count was removed to reduce redundancy.


### Modeling 

In this project, Logistic Regression, Random Forest and Gradient Boosting was utilised and compared based on evaluation metrics. It was found that Gradient Boosting performed the best compared to the other models with accuaracy of approximately 76% and ROC-AUC score of almost 59%. 

### Recommendations and Policy Interventions 

1. Dataset Improvements
-  Dataset shows class imbalances, with only 10.7% of them being only rejected. Monitor current applications 
-  Encourage the input of Type of Occupation to reduce missing values
-  Multicollinearity is found in some variables such as Number of Children and Family Members. Procedures like Principal Component Analysis may be useful prior to modelling. 

2. Modelling
- Although Gradient Boosting performed the best, it still suffers from class imbalances despite undergoing SMOTE. Alternative ensemble methods such as XGBoost could be explored to improve model performance.

3. Business World Implications
- Establish education initiatives regarding credit scores, and responsibility of credit card users to reduce default risk.
- Implement income-to-debt ratio thresholds to ensure users do not take in more debt than they already have.
- Implement a fair and transparent criteria for approval. Banks should provide clear explanations of rejections in order to reduce biasness and ensuring transparency. 
   

