# Electric Production Time Series

The purpose of this project was to build an accurate forecasting mode by analyzing monthly electricity production data.

## Technologies Used
- **Programming Languages**: R
- **Libraries**: dplyr, MASS, tidyverse, knitr, forecast, qpcR, astsa
- **Tools**: Git, GitHub

## Data
This project uses the Electric Production Dataset from Kaggle provided by Shenbagakumars, which includes approximately 400 observations, 2 columns, and has 29 years of data ranging from December of 1984 to 2017. The following columns are:

- DATE: The day the data was collected, formatted as DD/MM/YYYY.
- IPG2211A2N: The amount of units produced.

The data showed clear trends and seasonality, requiring proper differencing and transformations to achieve stationarity. Several models were assessed based on AICc, stationarity checks, and diagnostics. The chosen model's forecasts tracked closely within the 95% confidence intervals, indicating the model works well for forecasting electric production.  
