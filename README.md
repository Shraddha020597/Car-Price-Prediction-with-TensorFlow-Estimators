Car Price Prediction with TensorFlow Estimators
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This project builds and evaluates regression models using TensorFlow Estimators to predict car prices. It demonstrates key machine learning concepts by progressively adding complexity to the model's features.


What it Does 

Loads and Preprocesses Data: Reads car data from a CSV, identifies numeric and categorical features, handles missing values by filling them with zeros, and performs Z-score normalization on numeric features. Categorical features are converted using one-hot encoding (indicator_column).
Builds and Trains DNNs: Utilizes tf.estimator.DNNRegressor to create and train deep neural network models.
Feature Engineering Exploration: The project explores different model configurations:
A baseline model using only raw numeric features.
A model using normalized numeric features to see the impact of scaling.
A model built solely on one-hot encoded categorical features.
A comprehensive model combining both normalized numeric and one-hot encoded categorical features.

Evaluates Performance: Monitors model performance using average_loss during training and visualizes predictions against actual prices for numeric features to assess model fit.
