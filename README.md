# Rossmann-Sales-Prediction-

# Problem Description
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.
You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. 
Note that some stores in the dataset were temporarily closed for refurbishment.


# Table of Contents
1. Import Packages
2. Data Preparation

2.1 Load Dataset
2.2 Dealing With Missing Values
2.2.1 Count missing values in each dataset
2.3 Date Extraction
2.4 Joining Tables
2.5 Drop Subsets Of Data 
2.6 Feature Engineering
2.6.1 Create new variable "day_diff_comp"
2.6.2 Create new variable "day_diff_promo"

Exploratory Data Analysis
3.1 Correlation Heatmap
3.2 Sales across month
3.3 Effect of promo on sales
3.4 Sales vs School Holiday
3.5 Sales across days

Store Sales Prediction (Regression Models)
4.1 Linear Regression (OLS)
4.2 Random Forest Resgression
4.3 XGBoost Regresion
4.4 Decision Tree Regression

