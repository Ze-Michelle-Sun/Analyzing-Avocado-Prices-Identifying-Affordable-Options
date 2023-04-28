# Analyzing-Avocado-Prices-Identifying-Affordable-Options
## Introduction
Who doesn't love avocados? They are delicious, versatile, and packed with nutrients. However, their popularity often comes with a higher price tag. In this analysis, the aim to utilize data from the Hass Avocado Board website to uncover where the cheapest avocados can be found. The data, downloaded in May 2018 and compiled into a single CSV file, provides valuable insights into the retail scan data for national volume and price of Hass avocados.

## Exploratory Data Analysis (EDA)
Started by loading the data and performing some initial analysis. Imported necessary libraries such as Pandas, Matplotlib and Seaborn. Then, loaded the data from the CSV file using Pandas' read_csv() function. Once the data is loaded, checked for any missing values and duplicates, and look at the summary statistics using describe() function.

## Visualization
Created visualizations using Matplotlib and Seaborn libraries to explore the data further. Create a countplot to see the distribution of organic and non-organic avocados. Also created boxplots to compare the prices of organic and non-organic avocados and how they change over time. Lastly, created histograms to see the distribution of prices for both types of avocados.

## Classification
Performed a classification task to predict whether an avocado is organic or non-organic. Used Scikit-learn library to split the data into training and testing sets, preprocessed the data, and trained and evaluated different classification models such as Logistic Regression, Decision Tree, and Random Forest.

## Regression
Performed a regression task to predict the prices of avocados. Used Scikit-learn library to split the data into training and testing sets, preprocessed the data, and trained and evaluated different regression models such as Linear Regression, Ridge Regression, and Random Forest Regression.



## Conclusion
- After performing the above tasks, identified the regions where avocados are sold at cheaper prices. Can do this by analyzing the data by region and looking at the average prices of avocados in each region.

- By analyzing this comprehensive dataset, aimed to identify locations where avocados were available at more affordable prices. This analysis will provide valuable insights for avocado enthusiasts seeking cost-effective options without compromising on quality.
