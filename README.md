# Analyzing-Avocado-Prices-Identifying-Affordable-Options
## Introduction
Who doesn't love avocados? They are delicious, versatile, and packed with nutrients. However, their popularity often comes with a higher price tag. In this analysis, the aim to utilize data from the Hass Avocado Board website to uncover where the cheapest avocados can be found. The data, downloaded in May 2018 and compiled into a single CSV file, provides valuable insights into the retail scan data for national volume and price of Hass avocados.

## Exploratory Data Analysis (EDA)
- Started by loading the data and performing some initial analysis. 
- Imported necessary libraries such as Pandas, Matplotlib and Seaborn. 
- Loaded the data from the CSV file using Pandas' read_csv() function. 
- Checked for any missing values and duplicates, and look at the summary statistics using describe() function.

## Visualization
- Created visualizations using Matplotlib and Seaborn libraries to explore the data further. 
- Create a countplot to see the distribution of organic and non-organic avocados. 
- Created boxplots to compare the prices of organic and non-organic avocados and how they change over time.
- Created histograms to see the distribution of prices for both types of avocados.

## Classification
- Performed a classification task to predict whether an avocado is organic or non-organic. 
- Used Scikit-learn library to split the data into training and testing sets, preprocessed the data, and trained and evaluated different classification models such as Logistic Regression, Decision Tree, and Random Forest.

## Regression
- Performed a regression task to predict the prices of avocados. 
- Used Scikit-learn library to split the data into training and testing sets, preprocessed the data, and trained and evaluated different regression models such as Linear Regression, Ridge Regression, and Random Forest Regression.



## Conclusion
- Based on analysis using k-fold cross-validation for model selection, determined that the random forest model is the most suitable for predicting average avocado prices.
