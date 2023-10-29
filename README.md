# Rain-Prediction-Model

Here is a sample README for the rainfall prediction project:

# Rainfall Prediction in Australia 

This project applies logistic regression to predict whether it will rain tomorrow based on weather data from Australian weather stations.

## Data

The dataset contains daily weather observations from numerous Australian weather stations from 2008 to 2017. It has over 140,000 rows and includes columns for:

- Location
- Minimum temperature
- Maximum temperature   
- Rainfall
- Wind speed/direction
- Humidity
- Pressure
- Cloud cover
- Temperature at 9am & 3pm

The target variable is 'RainTomorrow' indicating whether it rained the next day.

## Model

The data is split into training, validation and test sets. A logistic regression model is trained on the training data. 

The model uses standard scaling and one-hot encoding to preprocess the numeric and categorical variables. It achieves ~84% accuracy on the test set.


## References

- The dataset is from Kaggle: https://www.kaggle.com/jsphyg/weather-dataset-rattle-package
- Logistic regression implementation uses Sklearn

## Contributing

Contributions to improve model accuracy are welcome!
