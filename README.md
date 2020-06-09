# Hydrology streamflow prediction with deep learning methods
This includes a work done for a project for CS230 Spring 2020 class. Deep learning models using GRU and LSTM techiques are explored to predict temporal distribution of streamflow downstream of the basin based on time-dependent hydroclimatic variables and static watershed basin attributes.

## LSTM network for Prediction in Ungauged Basins
LSTM based approach introduced in [1] is explored. The relevant code is used from [3]. The code used for exploring LSTM based approach is present in Milestone1 directory.

## GRU based netowrk to predict temporal distribution of streamflow downstream of the basin
GRU based network referred as "A-GRU" is explored to predict temporal distribution of streamflow downstream of the basin. The relevant code is used from [4]. The code developed for A-GRU is present in A-GRU directory. Please refer README file from A-GRU directory for instructions to train and evaluate A-GRU model.

## References:
[1] Frederik Kratzert, Daniel Klotz, Mathew Herrnegger, Alden K. Sampson, Sepp Hochreiter, Grey S. Nearing (2019). Toward Improved Predictions in Ungauged Basins: Exploiting the Power of Machine Learning, Water Resources Research. 
[2] Kratzert, F., Klotz, D., Shalev, G., Klambauer, G., Hochreiter, S., & Nearing, G. (2019). Towards learning universal, regional, and local hydrological behaviors via machine learning applied to large-sample datasets. Hydrology & Earth System Sciences, 23(12).  
[3] https://github.com/kratzert/lstm_for_pub  
[4] https://github.com/kratzert/ealstm_regional_modeling  
