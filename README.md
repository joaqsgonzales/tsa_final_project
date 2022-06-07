# TSA Final Project

Sharyl Sy & Joaqs Gonzales


In this notebook, we share how tsFresh could be integrated with machine-learning based time-series forecasting pipelines and deep learning models. tsFresh is an automated feature extraction library for time-series data which gets relevant trend and movement statistics from the time-series being modelled and then identifies which among these features are statistically significant in forecasting.

This repository attempts to make forecasts on the Dubai crude oil prices (actual levels) and returns, while using the CRB Commodity Index, the US Dollar Index, and Google Trend searches of the keyword "oil prices" as covariates for the model. This notebook attempts to compare the performance of tsFresh generated features extracted from the target time-series being modelled versus using proven covariates that attempts to explain the time-series data. From the notebook, we have learned that tsFresh could be used as a substitute for domain-specific explanatory variables in modelling time-series data. This could be helpful for data scientists who would like to make forecasts on time-series data where domain-knowledge is lacking.

To run the notebooks, install `conda` and then create an environment for this repository using the following command:

`conda env create -f environment.yml`

This creates an environment named `tsa-project` and installs all the required packages with the specified version according to the `tsa-project.yml` file specified here.

Afterwards, activate this environment using the command:

`conda activate tsa-project`
