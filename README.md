# Credit card customer churn prediction

![](https://images.unsplash.com/photo-1599050751795-6cdaafbc2319?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1100&q=80)
(Photo Credit: [cardmapr](https://unsplash.com/@cardmapr) on [Unsplash](https://unsplash.com/))
___

Credit card institutions use customer churning to predict who is going to stop using their credit card services. This churn metrics helps institutions improve customer retention.

This dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features.

Aknowledgements:
The original dataset can be found on this [website](https://www.kaggle.com/sakshigoyal7/credit-card-customers)

## Goal:
My goal is to predict customer churn from the dataset and gain some insights on how the bank can reduce the customer churn. 
___
## Table of Contents: 
1. Importing Libraries
2. Loading the Dataset
    * Load data into a Pandas DataFrame
    * Print the Datatypes of the dataset    
3. Data Cleaning
    * Remove the duplicates if any
    * Check for the null values in each column
    * Drop unnecessary columns - There are 2 columns which seem unnessary
4. Exploratory Data Analysis and Data Visualization  
    * Customer age distribution to see if customer age is normally distributed.
    * Proportion of customer gender **count** (countplot and piechart)
    * Proportion of existing and attrited customers **count**
    * Proportion of existing and attrited customers **by gender** (countplot and piechart)  
    * Proportion of entire education levels
    * Proportion of education level **by existing and attrited customer**
    * Proportion of education level **by gender** (pieplot and countplot)
    * Proportion of marital status **by attrited and existing customers** 
    * Correlation using heatmap
    * Proportion of income category
    * Proportion of income category by customer
    * Customer age count by customer
5. Customer Churn Prediction
    * Preprocessing to transform categorial to numerical to data prediction
    * Merge categorical and numerical dataframe
    * Test Train Split 
    * RandomForestClassifier
    * Model Building (du XGboost, random forest to find the best model score!
6. Conclusion
   * There are 16.07% of customers who have churned.
   * The proportion of gender count is almost equally distributed (52.9% male and 47.1%) compare to proportion of existing and attributed customer count (83.9% and 16.1%) which is highly imbalanced
   * The proportion of attrited customers by gender **there are 14.4% more male than female who have churned** 
   * **Customers who have churned are highly educated** - A high proportion of education level of attrited customer is Graduate level (29.9%), followed by Post-Graduate level (18.8%)** 
   * A high proportion of marital status of customers who have churned is Married (43.6%), followed by Single (41.1%) compared to Divorced (7.4%) and Unknown (7.9%) status  - **Marital stuats of the attributed customers are highly clustered in Married status and Single** 
   * As you can see from the proportion of income category of attrited customer, it is highly concentrated around $60K - $80K income (37.6%), followed by Less than $40K income (16.7%) compare to attrited customers with higher annual income of 80K-120K(14.9%) and over $120K + (11.5%). **I assume that customers with higher income doesn't likely leave their credit card services than meddle-income customer** 
___

:file_folder: [See my module](https://github.com/Conniekoh/credit_card_customer_churn_prediction/blob/main/codility/credit-card-customer-churn-prediction.ipynb)
___
## Before Release
- [x] Finish my changes
- [x] this is a complete item
- [ ] this is an incomplete item
