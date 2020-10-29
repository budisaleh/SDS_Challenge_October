# SDS_Challenge_October
this is for SDS challenge in October 
Using the SDS challenge I would like to develop a model to predict the used car price that customers are willing to pay given the following attributes:

manufacturer_name: the name of the car manufacturer
model_name: the name of the car model
transmission: the type of transmission the car has
color: the body color of the car
odometer_value: odometer state in kilometers
year_produced: the year the car was produced
engine_fuel: the fuel type of the engine of the car
engine_has_gas: whether or not the car has a propane tank with tubing
engine_type: the engine type of the car
engine_capacity: capacity of the engine in liters
body_type: the of body the car has
has_warranty: whether the car has warranty
state: the state of the car (new, owned, etc.)
drivetrain: type of drivetrain (front, rear, all)
feature_1 - feature_9: these features are boolean values about properties of the car
duration_listed: the number of days the car is listed in the catalog
price_usd: price of the car in USD
The model should predict:

Car Price
This exercise to find the best regression model based on the

Mean square error
Mean absolute error
r2 score
$$\begin{equation*}
MSE = {\frac{1}{n}\sum_{i=1}^{n}(y_{i} - \hat{y}_{i})^{2}}
\end{equation*}$$


Linear Model are using as follow :

Linear regression as baseline
Ridge
Lasso
KNN
Decission Tree
Random Forrest
Support Vector
