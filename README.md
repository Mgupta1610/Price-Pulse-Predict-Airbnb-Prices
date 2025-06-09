



# Price Pulse: Predicting Airbnb Prices

A machine learning project to predict Airbnb listing prices using features like location, room type, and reviews.

## Motivation

With the rapid growth of short-term rental platforms like Airbnb, pricing listings accurately has become crucial for hosts to maximize occupancy and revenue while remaining competitive. However, pricing is challenging due to many factors like location, property features, and seasonal demand. This project aims to build a predictive model that helps hosts set data-driven prices and assists guests in making informed booking decisions.

## Overview

This project analyzes Airbnb listings data to build a regression model that forecasts nightly prices. The goal is to help hosts price competitively and guests make informed booking decisions.

## Dataset

Public Airbnb dataset from 2020 containing ~50,000 listings with 17 key attributes such as price, room type, city, number of reviews, and amenities.

## Methodology

- **Data Cleaning:** Removed irrelevant columns, handled missing values, and filtered listings by California cities.
- **Feature Engineering:** One-hot encoded categorical variables (room type, city), applied log transformation on price for normalization.
- **Modeling:** Trained a linear regression model on the processed dataset.
- **Evaluation:** Model achieved R² = 0.85 with moderate RMSE and MAE, indicating reasonable predictive performance.

## Results

| Metric | Value  |
|--------|--------|
| R²     | 0.8535 |
| RMSE   | 0.6641 |
| MAE    | 0.4812 |

## Future Work

- Test more advanced regression techniques like Random Forest and XGBoost.
- Include geo-spatial features such as distance to landmarks.
- Deploy model as a web service with an interactive dashboard.
