# Deep learning network for Regional Rainfall-Runoff Modeling
Deep learning models using GRU and LSTM techiques are explored to predict temporal distribution of streamflow downstream of the basin based on time-dependent hydroclimatic variables and static watershed basin attributes as listed in [1].

## LSTM network for Prediction in Ungauged Basins
LSTM based approach introduced in [1] is explored. The relevant code is used from [2]. The code used for exploring LSTM based approach is present in Milestone1 directory.

## GRU netowrk to predict temporal distribution of streamflow downstream of the basin
GRU based network referred as "A-GRU" is explored to predict temporal distribution of streamflow downstream of the basin. The relevant code is used from [3]. The code developed for A-GRU is present in A-GRU directory.


## References:
[1] Kratzert, F., Klotz, D., Shalev, G., Klambauer, G., Hochreiter, S., & Nearing, G. (2019). Towards learning universal, regional, and local hydrological behaviors via machine learning applied to large-sample datasets. Hydrology & Earth System Sciences, 23(12).
[2] https://github.com/kratzert/lstm_for_pub
[3] https://github.com/kratzert/ealstm_regional_modeling
