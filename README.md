# Next Best Product Prediction Model for Financial Institutions

## Problem Statement and Introduction
Enhancing product utilization and increasing wallet share are critical objectives for financial institutions in a competitive market. Acquiring new customers is costly, thus leveraging existing customer relationships to cross-sell additional products is a more cost-effective strategy. In response, this project presents a data science model tailored to the banking industry, predicting the next best product for existing customers. By analyzing transaction histories and demographic information, the model offers optimal product recommendations aligned with individual customer preferences and financial needs.

## Dataset and Description
The dataset, sourced from Santander Bank, spans approximately 1.5 years, detailing customer product holdings such as credit cards and savings accounts. For this project, 30,000 records have been utilized.

## Exploring and Cleaning the Dataset
Data quality is assessed, and records with significant missing values are dropped. Categorical and numerical data types are specified, and missing values are handled accordingly. Product usage records with missing values are dropped, and 'NA' values are replaced with NaN.

## Visualize Product Usage
A visual representation of product usage is generated to understand customer behavior. This bar plot showcases the most frequently used products, aiding in identifying trends and preferences.

## Models
The XGBoost Multiclass Classifier is chosen to forecast the subsequent optimal product. The model is trained on customer characteristics to predict product recommendations effectively.

## Defining Pipeline
A preprocessing pipeline is defined to handle numerical and categorical columns efficiently. This pipeline is integrated with the XGBoost Multiclass Classifier to construct the full model pipeline.

##Hyperparameter Tuning
Grid search is employed to optimize the model's hyperparameters, enhancing its performance in predicting the next best product.

## Predicting the Next Best Products
The model predicts the top three best products for each customer based on their characteristics. Recommendations are generated, facilitating targeted marketing efforts and personalized customer experiences.

## Highest and Lowest Likelihood
Customers with the highest and lowest probabilities of product adoption are identified, enabling tailored marketing strategies for different customer segments.

This repository provides a comprehensive solution for financial institutions aiming to optimize product utilization and enhance customer satisfaction.

