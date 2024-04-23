# SC1015-FCSC-Group-1-Mini-Project
# Movie Revenue Prediction Analysis

## 1. Practical Motivation

This project explores the potential of data analysis in the entertainment industry, focusing on predicting box office revenues. Accurate revenue forecasts allow production companies, marketers, and distributors to make informed decisions regarding budgets, marketing strategies, and release schedules, optimizing resource allocation for both financial and critical success.

## 2. Problem Formulation

We aim to develop a predictive model for box office revenue by leveraging factors historically influencing a movie's financial performance.

## 3. Sample Collection

Data for this project was sourced from the IMDB movie database, encompassing variables such as cast, crew, budget, and genres. The dataset includes predefined 'train' and 'test' sets for model training and evaluation.

## 4. Data Cleaning

We focused on cleaning key dictionary-like columns including 'genres', 'cast', and 'production companies', replacing missing values with empty dictionaries and converting string representations into actual Python dictionary objects to maintain data uniformity.

## 5. Data Preparation

We transformed several columns ('belongs_to_collection', 'genres', 'production_companies', etc.) by counting items and extracting names to create aggregated strings per movie. Additionally, we implemented one-hot encoding to expand our dataset for detailed analysis.

## 6. Visualization

Our exploratory data analysis included:
- Scatter plots showing the relationship between movie budgets and revenue.
- Categorical plots analyzing revenue variance across different weekdays of release.
- Violin plots examining the revenue impact of specific actors.
- Dual-axis line charts exploring the relationship between the year of release and revenue.

## 7. Model Architecture

We used the LightGBM framework, a Light Gradient Boosting Machine suitable for handling large datasets and high-dimensional features, especially effective with categorical data.


## 8. Result Analysis

Our model configuration used the 'rmse' metric for optimization. Features like 'budget', 'popularity', and 'runtime' were identified as most influential in predicting revenue. We enhanced model robustness using K-Fold cross-validation and experimented with boosting variants like DART and GOSS to optimize feature importance analysis.


# Authors
Vaka Sreekethav, Rayapaty Yash, Saraf Harsha
Team 1, FCSC
