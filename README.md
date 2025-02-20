# Linear Regression for E-Commerce Data Analysis

## 1. Introduction
This project applies linear regression to analyze e-commerce data, aiming to predict customer spending based on available features. The objective is to build an accurate regression model to derive insights and improve business strategies.

## 2. Dataset Description
The dataset includes customer information and their annual spending. The key features are:

Avg. Session Length: Average time spent per session

Time on App: Time spent on the e-commerce mobile application

Time on Website: Time spent on the website

Length of Membership: Duration of customer membership

Yearly Amount Spent: Target variable representing annual customer spending

## 3. Methodology

Data Exploration: Used statistical analysis and visualization (histograms, pair plots, correlation heatmaps) to understand data distributions and relationships.

Data Preprocessing: Checked for missing values, outliers, and scaled numerical features if necessary.

Model Building: Implemented linear regression using Scikit-Learn to predict customer spending.

Model Evaluation: Assessed performance using metrics like R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## 4. Results and Evaluation
The linear regression model performed well with a high R-squared value, indicating strong predictive power. The most significant feature impacting spending was the Length of Membership, showing a strong correlation with the target variable.

## 5. Conclusion
The analysis suggests that customer spending is significantly influenced by their membership duration. Business strategies can leverage this insight by offering loyalty programs or exclusive deals to long-term members.
