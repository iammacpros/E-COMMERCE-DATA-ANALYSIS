# E-COMMERCE-DATA-ANALYSIS

## Project Overview

This project aims to analyze an e-commerce website logs data and build a model to determine whether customers are likely to return purchased product or not.

## Dataset Description
* Source [https://www.kaggle.com/datasets/kzmontage/e-commerce-website-logs]
* Rows ~ 172838
 ### Data Cleaning 
 * Removed rows with missing values
 * Rows after cleaning ~ 99457

---

## Exporatory Data Analysis
 * More females than males visited the site
 * Some genders were categorized as "Unknown" as they didn't create an account at the site
 * Most of the customers had premium membership accounts than normal membership accounts
 * Premium membership accounts where associated with females
 * Payments used to pay for goods were cash folloed by credit card
 * Goods were hardly returned after being bought
---
## Model Deployment
### Features used for model
* 'duration_(secs)'
* 'bytes'
* 'age'
* Encoded Categorical variables
   * 'gender', 'country', 'membership', 'language', 'pay_method', 'accessed_From', 'network_protocol'
 
 Target varible: 'returned'

 ### Model Trained:
 RandomForestclassifer()

 ### Train-Test-Split
 * 70% training, 30% testing

### Evaluation Metrics
Classification report from sklearn.metrics

---
## Tools Used 
* Python
* Visual Studio
* Jupyter
