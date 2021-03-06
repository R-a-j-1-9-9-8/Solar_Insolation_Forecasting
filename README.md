# Solar Insolation Forecasting

In this project the Solar Insolation value was predicted by using past data values.
Solar Insolation means The solar insolation is the actual amount of solar radiation incident upon a unit horizontal surface over a specified time for a given locality.

## Problem Statement

The techno-economical study for viability of any PV system requires accurately estimating the energy yield with an appropriate mathematical model. Different models were proposed for the prediction of PV module performance. However, these models mostly have a complicatedstructure requiring detailed knowledge of the parameters which are normally unavailable in the manufacturer’s data sheet. Therefore, such models are not suitable for output power calculation. It is the ambient temperature and solar irradiance meteorological data that govern the output of a PV system. Therefore, reliable temperature and radiation data should be readily available for the design of a techno-economically viable photovoltaic system. Because of the difficulties in installation, calibration, maintenance and high cost for measurement of these data, they are either not available or are only partially available at the installation site. Hence, the demand exists for the development of alternative ways to predict them. Solar irradiance is also characteristically variable; because of this, competent strategies of forecasting are required for enabling greater penetration of solar power. Influence of location, weather and other meteorological factors also make forecasting solar irradiance a challenging task. Therefore, for successful integration of solar energy with traditional generation supplies, the ability to accurately forecast solar irradiance is essential.


## File Descriptions

* <strong>[long1.csv](https://github.com/R-a-j-1-9-9-8/Solar_Insolation_Forecasting/blob/main/long1.csv)</strong> :- Data used for Training.
* <strong>[march.csv](https://github.com/R-a-j-1-9-9-8/Solar_Insolation_Forecasting/blob/main/march.csv)</strong> :- Data used for Testing.
* <strong>[deep_model.h5](https://github.com/R-a-j-1-9-9-8/Solar_Insolation_Forecasting/blob/main/deep_model.h5)</strong> :- Deep learning based LSTM model, which was trained in solar_deep.ipynb notebook.
* <strong>[solar_deep.ipynb](https://github.com/R-a-j-1-9-9-8/Solar_Insolation_Forecasting/blob/main/solar_deep.ipynb)</strong> :- This notebook describes
    * Time Series analysis
    * Creating dataset for forcasting
    * Model defining and training
    * Visualizing loss
    * Prediction
    * Calculating RMSE
* <strong>[solar_prophet.ipynb](https://github.com/R-a-j-1-9-9-8/Solar_Insolation_Forecasting/blob/main/solar_prophet.ipynb)</strong> :- This notebook describes
    * Basics of Prophet
    * Data Importing and Pre-Processing
    * Training the model
    * Prediction and Calculating RMSE

## Tools & Tecnologies Used:

* <strong>Python</strong>
* <strong>Pandas</strong>
* <strong>Numpy</strong>
* <strong>Matplotlib</strong>
* <strong>Seaborn</strong>
* <strong>statsmodels</strong>
* <strong>Microsoft Excel</strong>
* <strong>fbprophet</strong>
* <strong>TensorFlow</strong>
* <strong>Keras</strong>
* <strong>fbProphet</strong>
