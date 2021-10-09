# Short Term Weather Prediction
A Deep learning system to predict weather parameters of future such as Windspeed and Solar Radiation levels using Machine learning.

<h2>1. Background</h2>

This program implements a Recurrent Neural Network using LSTM architecture. The model is trained using Tensorflow(Keras) library on the weather forecast data of 2016 provided by the project guide. Data preprocessing is done using Pandas Dataframe. The dataset was sorted into train and validation sets. Weather forecast data of 2017 was used to test the model. Predicted values and real values are compared by plotting in a graph.


<h2>2. Dependencies</h2>
The programs were evaluated on Python 3.6 with the following versions of the dependencies:

| Package | Version |
| --- | --- |
|tensorflow-gpu|1.15.0|
|pandas|1.1.5|
|numpy|1.19.1|
|matplotlib|3.3.4|
|sklearn|0.23.2|

<h2>3. Executing the Programs</h2>

<h4>Preparing the programs and the dataset</h4>

1. Clone this repository  
`git clone https://github.com/avinashrox/Short-Term-Weather-Prediction.git`
2. Prepare the dataset:
	The training dataset is available at *./TrichyWeatherDataWindspeed/2016/csv/20162.csv*.
	The test dataset is available at */TrichyWeatherDataWindspeed/Formatted/20167.csv*.
3. Execute *weather_prediction_4hours.ipynb* in jupyter notebook for training the model with 2016 data and testing it with 2017 data.
