# Air Quality Prediction Models

This repository contains the implementation of Linear and Logistic Regression models from scratch, applied to air quality data. The project encompasses a comprehensive journey through data preprocessing, exploratory data analysis (EDA), model implementation, and results analysis. It aims to predict air quality levels using various environmental sensor data.

## Features
- **Data Preprocessing**: Cleaning and normalization of air quality data.
- **Exploratory Data Analysis**: Visualization and statistical analysis to understand data trends and relationships.
- **Linear Regression Implementation**: Custom-built linear regression model to predict continuous air quality indices.
- **Logistic Regression Implementation**: Custom-built logistic regression model for binary classification of air quality as high or low.
- **Performance Evaluation**: Evaluation of models using appropriate metrics; RMSE for Linear Regression and accuracy, precision, recall, and F1-score for Logistic Regression.
- **ROC Curve and AUC Analysis**: Analysis of the Logistic Regression model's performance through ROC curves and AUC scores.
- **Prediction on Test Data**: Applying the trained models to predict air quality on unseen test data.

## Dataset
The dataset comprises hourly averaged measurements from various sensors monitoring air quality. It includes concentrations of Non-Methane Hydrocarbons, Benzene, NOx, NO2, alongside sensor responses to these pollutants, and atmospheric conditions like temperature, relative humidity, and absolute humidity.

## Requirements
- Python 3.11
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (for preprocessing)

## How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Run the notebook (AirQualityPrediction-LinearLogisticRegression.ipynb) to see the analysis and model implementation.
