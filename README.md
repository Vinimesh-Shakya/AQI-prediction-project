# Air Quality Prediction Using Machine Learning

This repository contains a Jupyter notebook focused on predicting Air Quality Index (AQI) using various machine learning models. The project explores data processing, feature engineering, and the implementation of several regression models to predict AQI from environmental data.

## Overview

The goal of this project is to predict the Air Quality Index (AQI) based on various environmental features. AQI is a key indicator of air pollution and understanding its values can help in environmental monitoring and public health interventions.


## Dataset
Using the dataset Air Quality Data in India (2015 - 2020) from kaggle,
link: https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india

The dataset used contains the following features:
- **City**: Name of the city where data was recorded
- **Date**: Date of the data entry
- **PM2.5**, **PM10**, **NO**, **NO2**, **NOx**, **NH3**, **CO**, **SO2**, **O3**, **Benzene**, **Toluene**, **Xylene**: Various environmental factors measured in the air
- **AQI**: The Air Quality Index
- **AQI_Bucket**: A categorical classification of AQI values (e.g., Good, Moderate, Poor)

## Dataset Attributes

| Attribute    | Description                                     |
|--------------|-------------------------------------------------|
| `City`       | Name of the city where data was recorded        |
| `Datetime`   | Date and time of the data entry                 |
| `PM2.5`      | Particulate Matter < 2.5 µm (µg/m³)             |
| `PM10`       | Particulate Matter < 10 µm (µg/m³)              |
| `NO`         | Nitric Oxide (µg/m³)                            |
| `NO2`        | Nitrogen Dioxide (µg/m³)                        |
| `NOx`        | Nitrogen Oxides (µg/m³)                         |
| `NH3`        | Ammonia (µg/m³)                                 |
| `CO`         | Carbon Monoxide (mg/m³)                         |
| `SO2`        | Sulfur Dioxide (µg/m³)                          |
| `O3`         | Ozone (µg/m³)                                   |
| `Benzene`    | Benzene (µg/m³)                                 |
| `Toluene`    | Toluene (µg/m³)                                 |
| `Xylene`     | Xylene (µg/m³)                                  |
| `AQI`        | Air Quality Index                               |
| `AQI_Bucket` | Air Quality classification (Good, Moderate, etc.)|

## Features

- Preprocessing of AQI data
- Exploratory Data Analysis (EDA)
- Implementation of multiple machine learning regression models
- Performance evaluation using metrics like R² score

## Models Used

The following regression models have been implemented to predict AQI:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- AdaBoost Regressor
- Gradient Boosting Regressor
- K-Neighbors Regressor
- XGBoost Regressor
- Feed-Forward Neural Network

## Performance Evaluation

Model performance was measured using the R² score, with the following results:
- **Random Forest Regressor**: R² = 0.854
- **Feed-Forward Neural Network**: R² = 0.851
- **XGBoost Regressor**: R² = 0.833


## Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Vinimesh-Shakya/AQI-prediction-project
   ```
2. Run the notebook using Jupyter Notebook or JupyterLab.
   ```bash
   jupyter notebook
   ```
