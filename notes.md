# Dengue case Analysis and Forcasting

## State of the Problem
1) What are the effects of meteorological factors on the forecasting performance of the SEIR-SEI model for dengue cases in Cavite when analyzed in terms of:	
a) Temperature
b) Rainfall
c) Humidity

2) What are the effects of environmental and urbanization factors on the forecasting performance of the SEIR-SEI model for dengue cases in Cavite when analyzed in terms of:
a) Urbanization rate 
b) Population Density

3) What is the accuracy of the SEIR-SEI model in forecasting dengue cases in Cavite based on historical dengue case data?

4)  Is there any significant relationship between meteorological, environmental, and urbanization factors and the SEIR-SEI model’s forecasting performance for dengue cases in Cavite?


## Requirements (per SOP)

### SOP 1. Effects of meteorological factors (temperature, rainfall, humidity) on forecasting performance
Program outputs needed:
- Simulated dengue cases (forecasts) from SEIR-SEI model with meteorological factors included.
- Simulated dengue cases (forecasts) from model without meteorological factors.
*(Graphs showing dengue case forecasts alongside temperature, rainfall, humidity trends.)*

- FOR STATS: 
	- Forecast accuracy metrics (RMSE, R²) for both runs.
- Answers = Compare RMSE/R² of the two models. If accuracy improves when meteorological factors are included, then those factors have an effect.


### SOP 2. Effects of environmental & urbanization factors (urbanization rate, population density) on forecasting performance
Program outputs needed:
- Forecast results from model with population density & urbanization rate included.
- Forecast results from models without them.
*(Trend graphs of urbanization/pop density vs dengue cases.)*

- FOR STATS
	- Forecast accuracy metrics (RMSE, R²) for comparison.
- Answers = If including these variables lowers RMSE or raises R², then they improved the model’s performance.


### SOP 3. Accuracy of the SEIR-SEI model in forecasting dengue cases based on historical data
Program outputs needed:
- Simulated dengue cases (forecasts) from SEIR-SEI model.
**MAINLY NEEDED**
- Actual historical dengue cases (from DOH).
- Direct comparison chart (forecast vs. actual).

- GRAPH:
	- Residuals/error plots (difference between forecast & actual).
- For stats Validation metrics: RMSE, R², MAE (Mean Absolute Error optional).
- Answers = Report the error metrics. If R² is high and RMSE is low, the model is accurate.


### SOP 4. Significant relationship between meteorological, environmental, and urbanization factors and the SEIR-SEI model’s forecasting performance
Program outputs needed:
Correlation analysis (Pearson r) between:
Temp ↔ Dengue cases/forecasts
Rainfall ↔ Dengue cases/forecasts
Humidity ↔ Dengue cases/forecasts
Population density ↔ Dengue cases/forecasts
Urbanization rate ↔ Dengue cases/forecasts

-p-values for statistical significance. (STATS)
-Scatter plots with trendlines. (GRAPH)

It Answers: Show correlation coefficients. Strong significant r-values mean a strong relationship.

Summary of needed program outputs to answer all SOPs: 
1) Forecast vs. actual dengue cases (time-series).
2) Model runs with vs. without specific factors.
3) Graphs (trend lines, scatter plots, residual plots).
4) Forecast accuracy metrics (RMSE, R², MAE).
5) Correlation coefficients (r-values + p-values).