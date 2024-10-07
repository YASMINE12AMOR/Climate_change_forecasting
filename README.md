# Climate_change_forecasting
## Introduction
The notebook dives into the analysis of climate change, utilizing the Berkeley Earth Surface Temperature Study dataset. It covers extensive temperature reports from various sources, including historical inconsistencies and technological advancements in climate data collection.

## Project Objective
The primary aim is to analyze climate change through time series forecasting, focusing on temperature data. The project explores forecasting models to predict future trends based on historical climate data.

## Data Description
The dataset used is from the Berkeley Earth Surface Temperature Study, which includes global land temperature reports from multiple sources. The data is pre-processed to handle missing values and inconsistencies.

## Methodology
The methodology involves:

Data cleaning and preprocessing to address issues like missing values and inconsistent records.
Exploratory data analysis (EDA) to identify trends, seasonality, and anomalies in the dataset.
Implementing time series forecasting models, including ARIMA, SARIMA, and residual-based models.
## Modeling & Evaluation
The notebook evaluates different forecasting models, comparing them using AIC (Akaike Information Criterion) and BIC (Bayesian Information Criterion). Model.res is selected as the best-fit model based on its lower AIC and BIC values compared to SARIMA, Model1, and Model2.

## Results
The forecast results outline predictions for the next 48 time points in the univariate time series. Each lead forecast is provided along with its confidence intervals, offering insights into future temperature trends.
