# TransJakarta Passenger Forecasting Using ARDL

## About
This project analyzes daily TransJakarta passenger numbers and route adjustments using an Autoregressive Distributed Lag (ARDL) model in R. The analysis compares model specifications, evaluates diagnostic assumptions, and forecasts passenger numbers for early July 2024.

## Project Analysis
- [**View Full Analysis on RPubs**](https://rpubs.com/sandraberlianaputri/transjakarta-ridership-ardl-forecast)

## Dataset
- **Observation period:** January 1, 2023 – June 29, 2024
- **Number of observations:** 546 daily records
- **Response variable:** Daily TransJakarta passenger numbers
- **Explanatory variable:** Route adjustments
- **Data split:** 477 observations for training and 69 for testing

## Methods
- **Exploratory Data Analysis:** Visualizing daily passenger trends.
- **Lag Selection:** Using the Akaike Information Criterion (AIC) to identify candidate lag orders.
- **ARDL Modeling:** Comparing alternative lag specifications using `dLagM` and `dynlm`.
- **Diagnostic Testing:** Evaluating autocorrelation, residual variance, normality, and the residual mean.
- **Forecasting:** Generating forecasts and evaluating predictive accuracy using Mean Absolute Percentage Error (MAPE).

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
