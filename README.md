**UK Inflation (CPIH) Time Series Analysis & Policy-Relevant Forecasting (1989–2022)**

**Overview**

This project analyses long-term UK inflation dynamics using the **Consumer Prices Index including Owner Occupiers’ Housing Costs (CPIH)** from 1989 to 2022.
It applies **time-series decomposition and ARIMA** forecasting to identify historical trends, seasonal behaviour, and short-term inflation trajectories.

The analysis is designed to demonstrate how **data analytics and statistical modelling can support economic understanding and policy-relevant decision-making.**

## Key Visual Insights

### UK Inflation Trend (1989–2022)

![UK Inflation Trend](images/inflation_trend.png)

The chart shows the long-term evolution of UK inflation, highlighting:
- Elevated inflation in the early 1990s  
- A prolonged period of stability between 2010 and 2020  
- A sharp post-pandemic surge from 2021 onwards

### Trend and Seasonality Decomposition

![Seasonal Decomposition](images/decomposition.png)

Seasonal decomposition separates inflation into trend, seasonal, and residual components.  
The results indicate recurring monthly patterns alongside a clear long-term trend, supporting the use of time-series forecasting models.

### 12-Month Inflation Forecast (ARIMA)

![Inflation Forecast](images/forecast.png)

The ARIMA forecast suggests a gradual moderation of inflation over the next 12 months.  
The confidence intervals highlight uncertainty driven by external economic factors such as energy prices, monetary tightening, and geopolitical risks.

## Project Objectives

- Analyse long-term inflation trends in the UK economy (1989 to 2022)  
- Identify seasonal and structural patterns in CPIH data  
- Develop and interpret an ARIMA forecasting model
- Translate statistical outputs into meaningful economic insights  

## Why UK Inflation Matters

Inflation is a core indicator of economic stability and directly affects:

- Monetary policy decisions by the Bank of England  
- Business pricing and investment decisions 
- Household purchasing power and cost-of-living pressures
- Wage growth and labour market dynamics

By analysing inflation trends quantitatively, policymakers and analysts can better anticipate economic risks and design effective responses.

## Methodology

- Data cleaning and transformation into a monthly time series  
- Exploratory data analysis and trend visualisation  
- Seasonal decomposition to identify trend and recurring patterns  
- ARIMA(1,1,1) model development and fitting  
- 12-month out-of-sample forecasting  
- Model evaluation using standard error metrics  

## Model Performance

- **Mean Squared Error (MSE):** 6.36  
- **Mean Absolute Error (MAE):** 2.26  
- **Root Mean Squared Error (RMSE):** 2.52  

The results indicate reasonable short-term predictive accuracy for macroeconomic time-series data, while acknowledging uncertainty due to external shocks.

## Economic Interpretation

- Inflation is projected to stabilise around 3-4% toward the end of the forecast horizon
- This suggests gradual reversion toward the Bank of England's long-term inflation target
- The forecast supports expectations of easing inflationary pressure, subject to policy and external conditions

## Tools & Skills Demonstrated

- Python (pandas, matplotlib, seaborn, statsmodels)
- Time series analysis and forecasting
- ARIMA modelling
- Economic data interpretation
- Data visualisation and storytelling
- Model evaluation and validation

## Data Source

- **Dataset:** UK CPIH (Consumer Prices Index including Owner Occupiers’ Housing Costs)  
- **Time Period:** 1989–2022  
- **Publisher:** Office for National Statistics (ONS)  
- **Licence:** Open Government Licence v3.0  
- **Accessed via:** Kaggle  

## Future Enhancements

- Incorporate exogenous macroeconomic variables such as interest rates, GDP, and energy prices 
- Compare ARIMA with SARIMA and multivariate time-series models  
- Extend analysis to CPI and RPI inflation indices  

