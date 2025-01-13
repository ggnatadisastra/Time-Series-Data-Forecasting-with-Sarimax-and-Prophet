# Yellowfin Tuna Catch Forecasting

This project aims to forecast the yellowfin tuna catch using time series analysis and machine learning models. The dataset contains fishing catch data over several years, including various tuna species. The project includes several data preprocessing steps, exploratory data analysis (EDA), and model building using **SARIMAX**, and **Prophet** to predict future catches.

## Project Overview

This project includes the following steps:

1. **Data Preprocessing:**
   - Loading the dataset and cleaning the data.
   - Converting categorical and geographic variables into numeric formats.
   - Handling incomplete data.
   - Aggregating the data to the necessary time units (monthly, yearly).

2. **Exploratory Data Analysis (EDA):**
   - Visualizing the distribution of catch values by species.
   - Analyzing trends in tuna catches over time.
   - Checking seasonality and patterns using ACF and PACF plots.
   - Evaluating stationarity of the time series using rolling mean and standard deviation.

3. **Model Building:**
   - **SARIMAX** model for incorporating seasonality and trend components.
   - **Prophet** model for time series forecasting with seasonality and holidays.

4. **Model Evaluation:**
   - Evaluating the models using error metrics such as MSE, RMSE, and MAE.
   - Comparing the forecasted results with the actual data.

## Data Source

The data used in this project is sourced from the **Western & Central Pacific Fisheries Commission (WCPFC)**. The dataset is publicly available and can be downloaded from the following link:

[WCPFC Aggregated Catch Effort Data](https://www.wcpfc.int/wcpfc-public-domain-aggregated-catcheffort-data-download-page)

## Requirements

To run the project, you will need to install the following dependencies:

```bash
pip install prophet
pip install pmdarima
pip install matplotlib
pip install seaborn
pip install pandas
pip install numpy
pip install statsmodels
