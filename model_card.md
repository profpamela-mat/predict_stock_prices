# Model Card


## Model Description

**Input:** 
- 'open' - Opening price
- 'high' - Highest price reached during the day
- 'low' - Lowest price reached during the day
- 'adjclose' - Closing price adjusted for actions such as dividends and stock splits, which affect the price of a stock over time. 

**Output:** 
- 'close' - Closing price

**Model Architecture:** Linear Regression

## Performance

As the model used was Linear Regression, the Coefficient of Determination (R²) was used, which is a measure of how well the model fits the data. It varies from 0 to 1, with values closer to 1 indicating a better fit of the model to the data. To calculate this metric, the test data (30% of the data initially separated) was used, and the value obtained was 0.9999241018102808.

## Limitations

This model does not consider external news that may affect asset prices, such as changes in the economy, politics, or global events. It also assumes that there is a linear relationship between the variables, which may not be true in all situations.

