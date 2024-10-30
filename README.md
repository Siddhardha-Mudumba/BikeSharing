## Project

Bike Sharing Demand Prediction
This project investigates the factors influencing bike sharing demand in a city. It utilizes a machine learning model to predict
the number of bike rentals based on various weather, seasonal, and calendar-related variables.

## Data Description
The project utilizes a dataset containing information on bike rentals, including:

Weather conditions (season, weather type, temperature, etc.)
Calendar information (year, month, holiday, weekday, working day)
Rental counts (casual rentals, registered rentals, total rentals)
The total rental count ("cnt") is the sum of casual and registered rentals.

## Methodology
The project employs Ordinary Least Squares (OLS) regression to build a model that predicts the total rental count based 
on the provided variables. The model analyzes the relationships between these variables and the rental counts to identify 
the most influential factors.

## Results and Discussion
The model successfully explains a significant portion (around 87.6%) of the variation observed in rental counts. 

The analysis revealed that:
Positive Influences: Temperature, "feels like" temperature, and certain seasons (summer, winter) are positively correlated 
with bike rentals.
Negative Influences: Wind speed, and specific weather conditions (light snow, mist) tend to decrease bike rentals.
Other Factors: The model also considers the impact of holidays, working days, and specific months on rental demand.

## Conclusion
This project demonstrates the feasibility of leveraging machine learning to predict bike sharing demand. 
The identified factors provide valuable insights for city planners to optimize bike infrastructure and resource allocation 
based on predicted demand.


## Technologies:
Programming Language (Python)
Machine Learning Library (statsmodels)
Data Analysis Tools (pandas)


## Contact
- Siddhardha Mudumba
