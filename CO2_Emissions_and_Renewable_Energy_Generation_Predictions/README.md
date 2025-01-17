# CO2 Emissions and Renewable Energy Generation Predictions for Norway in 2030

This repository contains the analysis, data preparation, and machine learning models used to predict CO2 emissions and renewable energy generation in Norway by 2030. Using Ensemble Learning and SARIMA models, this project provides insights into the feasibility of Norway's green energy transition and its impact on CO2 emissions.

---

## Introduction
Norway aims to achieve carbon neutrality by 2030 by reducing CO2 emissions and fully transitioning to renewable energy. This project explores the potential of achieving these goals by analyzing historical energy and emissions data and forecasting trends using machine learning.

### Objectives
1. Predict Norway's CO2 emissions for 2030.
2. Forecast renewable energy generation trends through 2030.
3. Provide insights into Norway's transition toward a sustainable energy future.

---

## Data Sources
The primary dataset used is the [Ember Monthly Electricity Data](https://ember-climate.org/data-catalogue/monthly-electricity-data/), which contains monthly energy generation, emissions, and demand data from 2015 to 2023. Key features include:
- Electricity generation by source.
- CO2 emissions and intensity.
- Energy demand and imports.

---

## Methodology
### Data Preparation
1. **Extraction and Cleaning**: Filtered Norway-specific data and removed redundant columns.
2. **Standardization**: Converted all energy units to terawatt-hours (TWh) and emissions to metric tons (mtCO2).
3. **Feature Engineering**: Created daily datasets using linear interpolation for finer granularity.

### Machine Learning Models
1. **CO2 Emissions Prediction**:
   - Multi-Layer Perceptron (MLP) Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Ensemble Voting Regressor
2. **Renewable Energy Generation Forecast**:
   - SARIMA (Seasonal Autoregressive Integrated Moving Average) model

### Performance Metrics
- RMSE (Root Mean Square Error)
- R² Score
- Explained Variance

---

## Library Used
- **Python**: Data processing and modeling.
- **Pandas**: Data cleaning and transformation.
- **Scikit-Learn**: Machine learning models.
- **Statsmodels**: Time series forecasting.
- **Matplotlib & Seaborn**: Data visualization.

---

## Results
### CO2 Emissions Prediction
- Predictions indicate a substantial reduction in CO2 emissions by 2030 if current trends continue.

### Renewable Energy Generation Forecast
- SARIMA model forecasts an increase in renewable energy generation, primarily from hydroelectric and wind sources.
- By 2030, renewables are predicted to contribute significantly to Norway's energy mix.
