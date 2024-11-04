# Used Vehicle Price Prediction

A machine learning project to forecast used vehicle selling prices based on automotive attributes, aimed at providing accurate pricing estimates for car dealers, buyers, and sellers.

## Business Value

- **Car Dealers**: Optimize inventory pricing and trade-in valuations
- **Buyers**: Make informed purchasing decisions with fair price estimates
- **Sellers**: Set competitive market prices based on vehicle attributes

## Model Evaluation

Performance is measured using Root Mean Square Error (RMSE), which quantifies the difference between predicted and actual prices.

## Dataset Overview

### Variables
- **Numerical Features (14)**: Including price, horsepower, year, engine displacement, fuel economy metrics, and mileage
- **Categorical Features (23)**: Including VIN, body type, colors, transmission, make/model, and dimensions

### Data Quality
- Training set: 1,807 missing values across 19 variables
- Test set: 2,597 missing values across 26 variables
- Key variables with gaps: interior color, mileage, torque, fuel economy, power, transmission, engine type

### Characteristics
- Wide value ranges with notable outliers
- Positive correlations between price and newer vehicle attributes
- Negative correlations with lower efficiency metrics
- Skewed distributions with concentration around intermediate values