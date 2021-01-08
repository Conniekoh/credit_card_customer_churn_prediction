# Credit card customer churn prediction

![](https://images.unsplash.com/photo-1599050751795-6cdaafbc2319?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1100&q=80)
(Photo Credit: [cardmapr](https://unsplash.com/@cardmapr) on [Unsplash](https://unsplash.com/))
___

Credit card institutions use customer churning to predict who is going to stop using their credit card services. This churn metrics helps institutions improve customer retention.

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
    * Replace target value (existing customer/attired customer)
    * Customer age distribution to see if customer age is normally distributed.
    * Proportion of customer gender count
    * Proportion of existing and attrited customers vs gender (countplot and piechart)  
    * Proportion of entire education levels
    * Proportion of education level by existing and attrited customer
    * Proportion of education level by gender (pieplot)
    * Proportion of education level by gender (countplot)
    * Proportion of marital status by attrited and existing customers 
    * Correlation using heatmap
    * Proportion of income category
    * Customer age count by customer
5. Customer Churn Prediciton
    * Preprocessing to transform categorial to numerical to data pridiction
    * Merge categorical and numerical dataframe
    * Test Train Split 
    * RandomForestClassifier
    * Model Building (du XGboost, random forest to fnd the best model score!
6. Conclusion

:file_folder: [See my module](https://github.com/Conniekoh/Web-Scrapping/blob/master/codility/How%20to%20Scrap%20News%20Article.ipynb)
___
## Before Release
- [x] Finish my changes
- [x] this is a complete item
- [ ] this is an incomplete item
