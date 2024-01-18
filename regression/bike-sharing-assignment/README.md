# Forecast Hourly Bike Rental Demand

Problem Statement

## Summary

### Exploratory Data Analysis

During exploratory data analysis, the following insights were found:

- The distribution of the dependent variable, which is the number of bikes rented per hour, is right-skewed so the majority of bikes rented per hour are less than 200 individual bikes.

- Summer and fall seasons have higher bike rentals per hour than spring and winter seasons, on average.

Hourly bike demand is heavily influenced by weather conditions. A good weather condition increases bike demand hourly, while a bad weather condition decreases it.

- Holidays and working days have almost no effect on the hourly bike demand.

- The overall demand for bikes increases in the evening.

- On working days, the demand is highest in the morning and evening, while on non-working days, it is highest in the afternoon.

- There is a moderate positive correlation coefficient of 0.40 between the number of bikes rented per hour and temperature. This means that as the temperature increases, bike demand also increases at a moderate rate. This finding supports the assumption that bike demand increases in the summer and fall seasons, where the temperature is typically higher.

### Feature Importance

The feature importance visualization indicates that the following are the main drivers for predicting hourly bike demand:

- Hour
- Temperature
- Working day

The following features are also important for predicting hourly bike demand:

- Humidity
- Year

However, the following features are not important for prediction:

- Season
- Holiday
- Windspeed