# FCSC Team 1 Mini Project

## Description

This project aims to predict box office revenue using data analysis within the entertainment industry. It serves as a crucial tool for production companies, marketers, and distributors to make informed decisions about budgets, marketing strategies, and release schedules, ultimately optimizing resource allocation and enhancing a film's success.

## Data Extraction

Data for this project was extracted from the IMDB movie database, which includes crucial features such as cast, crew, budget, and genres. The dataset is segmented into 'train' and 'test' sets to facilitate the modeling process.

## Data Cleaning

The data cleaning process focused on dictionary-like columns such as 'genres', 'cast', and 'production companies'. Missing values in these columns were replaced with empty dictionaries to maintain uniformity. Additionally, string representations of dictionaries were converted into actual Python dictionary objects to facilitate further analysis.

## Data Preparation

During data preparation, several transformations were applied to columns such as 'belongs_to_collection', 'genres', 'production_companies', 'production_countries', 'spoken_languages', 'keywords', 'cast', and 'crew'. Operations included counting items, extracting names to create aggregated strings of relevant items per movie, and applying one-hot encoding to expand the dataset for detailed analysis.

## Data Exploration

The exploratory data analysis included visualizing relationships between various movie features and revenue, such as budget, cast, and release day. Techniques such as scatter plots, violin plots, and dual-axis line charts were used to uncover trends and correlations, providing insights into factors influencing box office success.

## Machine Learning

The project utilized LightGBM, a machine learning framework suited for handling large datasets with high-dimensional features. The model was tuned and evaluated using Root Mean Squared Error (RMSE) and enhanced with K-Fold cross-validation to ensure robustness and reliability. Further experiments with variants like DART and GOSS highlighted different aspects of feature importance, aiding in the selection of the most effective model configuration.

## Usage

To run this project, ensure all dependencies are installed as outlined in the initial code cells of the notebook. Load the data, follow the notebook's sequential steps for data processing, exploration, and machine learning modeling, and apply the learned models to make revenue predictions.


## Authors

- Vaka Sreekethav
- Rayapaty Yash
- Saraf Harsha
