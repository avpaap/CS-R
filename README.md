# Capstone Project: Customer Segmentation and Prediction


## Installation <a name="installation"></a>
Besides the libraries included in the Anaconda distribution for Python 3.6 the following libraries have been included in this project:
* `LGBM` -  gradient boosting framework that uses tree based learning algorithms.
* `XGBoost` - optimized distributed gradient boosting library designed to be highly efficient, flexible and portable.
* `skopt` - simple and efficient library to minimize (very) expensive and noisy black-box functions.

## Introduction <a name="introduction"></a>
This project is a part of Udacity Machine Learning Engineer Nanodegree Capstone Project in collaboration with Bertelsmann Arvato. Demographic information of customers of a mail order company dealing with organic products was analyzed with demographic information of general population of Germany to identify customer segments and data of mail order marketing campaign was used to predict customer conversion. The datasets were provided by Arvato. The data is protected by terms and conditions by Arvato and is not available for use by general public.

Customer Segmentation was performed using Unsupervised learning to identify the parts of the population that best describes the core customer base of the company.
With above analysis, Supervised learning was applied on marketing campaign data to predict which individuals are likely respond or becoming customer. Performance scoring was done be uploading the prediction to Kaggle Competition.
Results of the performance of my model on Kaggle can be found here
https://www.kaggle.com/c/udacity-arvato-identify-customers/leaderboard


## Files <a name="files"></a>
The data provided by Arvato is as follows

• Azdias — Demographics data for the general population of Germany (891 211 x 366).
• Customers — Demographics data for customers of the German mail-order company (191 652 x 369).
• Mailout_train (train) — Demographics data for individuals who were targets of a marketing campaign (42 982 x 367).
• Mailout_train (test) — Demographics data for individuals who were targets of a marketing campaign (42 833 x 366).
• DIAS Attributes — Values 2017.xlsx — a data dictionary of the columns including description, possible values, and what the values mean.
• DIAS Information Levels — Attributes 2017.xlsx — indicates the information level for each column (Person, Household, Building, etc)

feature_summary_complete.csv was manually created using two DIAS description files. This file contains attribute, information level, data type, missing or unknown values.


## Results <a name="results"></a>
Clusters of relevance of future customers and positive responders to the mail-order campaign was identified successfuly.
For details of this projects please go through the attached report.

## Author
Ambresh Patil
