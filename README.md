# Data-Driven-Attribution-of-Climate-Events 
***
<br>

### 1st Step: Reproduce the Paper from Badr et al (2014) 'Application of Statistical Models of the Prediction of Seasonal Rainfall Anomalies over the Sahel'

Note: The underlying data used here is not always the same as in Badr et al. (2014).\
In general I used the most recent versions of the single data sets.

- **nb_badr01_sahelrainfall.ipynb** plots a time series from the Sahel Precipitation Index (**SPI**).

- **nb_badr02_boxcorr.ipynb** box-correlates the SPI with global Surface Temperature.

- **nb_badr03_pred_indices.ipynb** reproduces Badr's predicor indices

- **nb_badr04_pred_pca.ipynb** applies PC decomposition to the whole set of predictor variables

- **nb_badr05_pred_nn.ipynb** sets up and rund a simple Neural Network for summer rainfall prediction

- **nb_ersst_data.ipynb** merges the single ERSST Data files into one netCDF file.

- For the model prediction Badr et al. (2014) used a total set of 20 predictor variables.\
    In nb_predictor_indices.ipynb the according 20 AMJ predictors are computed.

