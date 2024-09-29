# AQI-prediction-project
In this project, the goal is to predict Air Quality Index (AQI) using a variety of regression models and a deep learning approach.
Using the dataset Air Quality Data in India (2015 - 2020) from kaggle,
link: https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india

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
