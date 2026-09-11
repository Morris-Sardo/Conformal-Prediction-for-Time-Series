# Conformal-Prediction-for-Time-Series
This project adopt conformal prediction on various time series modes.


## INTRODUCTION
This project explores the application of conformal prediction methods to time-series forecasting. 
Three conformal prediction approaches are implemented and evaluated: Weighted Conformal Prediction (WCP), Ensemble Batch Prediction Intervals (EnbPI) and Adaptive Conformal Inference (ACI).

The methods are evaluated across four different time-series settings: AR(1), ARMA(1,1), Mean Shift, and GARCH(1,1). The aim of the project is to investigate how the different conformal prediction methods behave under different time-series dynamics, with particular attention to empirical coverage, 
prediction interval width, and computational running time.

## INSTALLATION INSTRUCTION AND SET UP
- intstall JuperNotebook
- git clone <repository_url>
- install numpy 
- install matplotlib 

## DATASETS 
Four synthetic time series are considered: AR(1), ARMA(1,1), Mean Shift, and GARCH(1,1). Each time series is transformed into a supervised dataset using a lag of three. Each input X_t contains three consecutive observations, while the following observation Y_{t+1} is used as its corresponding label.

For Weighted Conformal Prediction (WCP) and Adaptive Conformal Inference (ACI), the dataset is divided into training, calibration, and test sets. Ensemble Batch Prediction Intervals (EnbPI) instead uses bootstrap samples and out-of-bag (OOB) observations.

## REFERENCES
[1] Stocker, M., Małgorzewicz, W., Fontana, M. and Taieb, S.B., 2025. A gentle introduction to conformal time series forecasting. arXiv preprint arXiv:2511.13608.

*A Gentle Introduction to Conformal Time Series Forecasting.*
Available at: https://arxiv.org/abs/2511.13608


