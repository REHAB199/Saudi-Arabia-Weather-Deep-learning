
# Makkah-Region-Weather-Deep-Learning

# Abstract:
Weather forecasting is one of the most important types of forecasting because agriculture sectors as well as many industries are largely dependent on the conditions of weather 
* The present technology uses numerical model based weather worked on one day ahead prediction of weather parameters proposed 
* A method to forecast rainfall data in the rainy season through artificial neural networks
* That the feature based forecasting model can make predictions with high degree of accuracy
 *There is a scope of improvement in the accuracy of forecasts made by these models when considering the benefits that it has.

# Design:
In google colab to predict weather history such as temperature, wind, humidity, barometer, and visibility.The model has been trained using past 3 years of real data collected from(2017-2019) and tested over 4 years to forecast weather history such as temperature, wind, humidity, barometer, and visibility.. The results based on mean square error function
(MSE) confirm, this model which is based on multilayer perceptron has the potential to successful application to weather forecasting.

# Data:
The data used in this project are the  hourly historical weather data for Makkah city from 2017 to 2019. Included a date for which you would like to see weather such as temperature, wind, humidity, barometer, and visibility, collected on an hourly basis, and there are no missing values.

# Algorithms:
* We applied different Models techniques (LSTM, Biderictinal LSTM, Stacked LSTM big & Small)
, and applied feature extraction technique RMSE to extract the most important features from the Weather files and then we applied neural network algorithms using dense layers with relu activation functions.

We create a baseline model (Lag1 RMSE: 0.007128024)&(lag2 RMSE: 2.215565)
![WhatsApp Image 2022-01-20 at 1 53 41 PM](https://user-images.githubusercontent.com/79373504/150328009-f85e9f2d-5a5b-42f8-86db-f579f90d07de.jpeg)



# Tools:
* Jupyter Notebook.
* Google Colab.
*	Numpy and Pandas for data manipulation.
*	Matplotlib, rcParams and Seaborn for plotting.
*	Sklearn-Scikit-learn.
*	Tensorflow.
*	Keras.
*	Scipy.
*	Statsmodels.
*	Math.
*	Calendar.

