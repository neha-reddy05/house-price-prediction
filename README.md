# house-price-prediction
Project Overview
This project aims to build a linear regression model to predict house prices based on key property features. By analyzing historical data, we can identify relationships between house attributes such as the number of bedrooms, bathrooms, and size to estimate a home's market value.

Dataset Features
The dataset contains the following columns:

beds: Number of bedrooms in the house.
baths: Number of bathrooms in the house.
size: Total living area of the house.
size_units: Measurement unit of the size (e.g., square feet, square meters).
zip_code: Geographic location identifier for the house.
price: The actual sale price of the house (target variable).
Approach
Data Preprocessing: Handle missing values, standardize units, and encode categorical variables if needed.
Exploratory Data Analysis (EDA): Visualize data distributions and correlations between features.
Feature Engineering: Convert categorical variables into numerical values and scale numerical features.
Model Training: Train a linear regression model to learn the relationship between house attributes and price.
Expected Outcome
The trained model will provide price predictions based on property details, helping buyers, sellers, and real estate professionals make data-driven decisions.
