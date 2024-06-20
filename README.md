# Market-Basket-Analysis-for-Amazon-Product-Recommendation

Conducted Market Basket Analysis (MBA) on Amazon product dataset to enhance recommendations. Identified top-selling products and top products in each category using review count. Implemented association rule mining for personalized recommendations. Evaluated effectiveness through metrics.

## Overview

Market Basket Analysis is a data mining technique used to uncover associations between products purchased together by customers. In this project, we utilize MBA to identify patterns in Amazon product purchases, allowing us to generate personalized product recommendations for customers based on their shopping history.

## Dataset

Amazon product dataset from Kaggle 

## Data Preprocessing

1. **Data Collection**: Transactional data including user IDs, product IDs, and quantities purchased.
2. **Data Cleaning**: Removing duplicates, handling missing values.
3. **Data Transformation**: Converting data into transaction-level and basket-level formats.
4. **Data Encoding**: One-hot encoding for categorical variables.
5. **Transaction Filtering**: Removing low-support and irrelevant items.
6. **Association Rule Mining**: Using Apriori or FP-Growth algorithms.

## Exploratory Data Analysis

- Summary Statistics
- Distribution of Numerical Variables
- Correlation Analysis
- Categorical Variables Analysis
- Text Analysis

## Feature Selection and Generation

- Selection of relevant attributes for analysis or modeling.
- Creation of new features such as WeightedSum and subcategory columns.
- Summarization by subcategory and selection of top products.

## Linear Regression using Ridge Regression Model and Polynomial Regression

- Polynomial Features: Creating polynomial features from original features.
- Ridge Regression: Handling multicollinearity and reducing overfitting.
- Model Evaluation: Cross-validation, MSE calculation, and model accuracy.
- Visualization: Scatter plots, residual plots, and histograms.

## Top Recommended Products

<img src="https://github.com/atharva-narkhede/Market-Basket-Analysis-for-Amazon-Product-Recommedation/assets/106006803/4fc877f3-ffb9-48ff-89cf-2e2dde19eb07" width="800">

## Project Contributors

- Prafull Raj | AP21110011016
- Atharva Narkhede | AP21110011028
- Rahul Bajaj | AP21110011022
- Vrijeshwar Singh | AP21110010922
- Aditya Dubey | AP21110010729

### Under the Guidance of Murali Krishna Enduri, SRM University – AP, Andhra Pradesh
