# Electricity consumption forecasting with LSTMs

### This is an adaptation of a tutorial on LSTM's on [machinelearningmastery.com](https://machinelearningmastery.com/how-to-develop-lstm-models-for-multi-step-time-series-forecasting-of-household-power-consumption/#comment-494688)
The repo is a way for me to confirm understanding applications of LSTM's and to get hands-on practice setting one up.

### Setup
Download the source data from the tutorial link and save it to the data directory.

### Running

Data prep:
Munge.py fills in missing values, adds engineered feature and parses dates.
Downsample.py resamples minute-level data to daily data.

Model:
train.py 

### Notes
Updated run is multivariate input (all variables in dataset) from previous 2 weeks to predict next week's power consumption
using an LSTM encoder-decoder architecture.
RMSE of 391 on this run.  

