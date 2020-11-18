# Data-Driven-Attribution-of-Climate-Events

### 1st Step: Reproduce the Paper from Badr et al (2014) 'Application of Statistical Models of the Prediction of Seasonal Rainfall Anomalies over the Sahel'

Note: The underlying data used here is not always the same like in Badr et al. (2014).\
In general I used the most recent versions of the single data sets.

- In the nb_sahelrainfall.ipynb plot a time series from the Sahel Precipitation Index (SPI).

- The nb_boxcorr.ipynb box-correlate the SPI with global Surface Temperature date.

- The nb_ersst_data.ipynb merges the single ERSST Data files into one netCDF file.

- For the model prediction Badr et al. (2014) used a total set of 20 predictor variables.\
    In nb_predictor_indices.ipynb the according 20 AMJ predictors are computed.
