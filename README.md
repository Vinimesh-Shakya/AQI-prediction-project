# AQI-prediction-project
In this project, the goal is to predict Air Quality Index (AQI) using a variety of regression models and a deep learning approach.
Using the dataset Air Quality Data in India (2015 - 2020) from kaggle,
link: https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india

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


I employed seven different regression algorithms to find the most accurate predictor of AQI. These models include:
# Models : R2-score
- Linear Regression : 0.732
- Decision Tree Regressor : 0.693
- Random Forest Regressor : 0.854
- AdaBoost Regressor : 0.383
- Gradient Boosting Regressor : 0.802
- K-Neighbors Regressor : 0.840
- XGBoost Regressor : 0.833

Additionally, I implemented a **Feed-Forward Neural Network (FFNN)** trained over **150 epochs** to capture complex non-linear patterns in the data.
**Also got R2-score of 0.851**

# Best Model Performance
- The Random Forest Regressor achieved the highest performance, with an R² score of 0.854.
- The Feed-Forward Neural Network followed closely with an R² score of 0.851.
- The K-Neighbors Regressor following R² score of 0.840.
- The XGBoost Regressor also performed well, with an R² score of 0.833.
