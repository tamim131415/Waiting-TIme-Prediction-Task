# Real-Time Waiting Time Prediction

## Introduction
This project implements a *real-time waiting time prediction system* using a *Random Forest Regressor (RFR)* model. The system allows users to *select a service name*, and it automatically calculates the expected waiting time based on historical transaction data. The model uses features such as:
- *Encoded Service Name*
- *Arrival Time (in seconds)*
- *Arrival Day, Month, and Year*



## Model
- *Models*: Random Forest Regressor (RFR), Decition Tree Regression (DTR), Linear Regression (LR) and XGBoost Regression
- *Feature Set*: Encoded service name, timestamp features

## Installation
To set up the environment, use the provided environment.yml file.

## Create and Activate the Environment
conda env create -f environment.yml

conda activate time_prediction_env


## Results
In real-time prediction, users can select a *service name, and the system predicts the waiting time in real-time. The model achieves **high accuracy and fast inference* by leveraging optimized pre-processing and caching mechanisms.

