# Real-Time Waiting Time Prediction

## Introduction
This project implements a *real-time waiting time prediction system* using a *Random Forest Regressor (RFR)* model. The system allows users to *select a service name*, and it automatically calculates the expected waiting time based on historical transaction data. The model uses features such as:
- *Encoded Service Name*
- *Arrival Time (in seconds)*
- *Arrival Day, Month, and Year*

## Folder Description
- Dataset folder contains Foramatted Dataset and Preprocessed Dataset.
- Docs folder contains a brief document explaining our approach, assumptions, and decisions.
- Images folder contains all images representing visualization.

## File Description
- analysis.ipynb contains all preprocessing steps.
- visualization.ipynb contains all data visualization approaches.
- main.ipynb contains training pipeline, model evaluation, XAI and real-time prediction.


## Model
- *Models*: Random Forest Regressor (RFR), Decition Tree Regression (DTR), Linear Regression (LR) and XGBoost Regression
- *Feature Set*: Encoded service name, timestamp features

## Evaluation Model
- Please create a Models folder and download the trained model from these:
  - [Random Forest Regression](https://drive.google.com/file/d/1e8cOJ9voO6K074kUMVGZ-vGyQZNPw18u/view?usp=drive_link)
  - [XGBoost Regression](https://drive.google.com/file/d/1xxBbn5MtwXZn5babVGpWbQJC-tha9P0Q/view?usp=drive_link)

## Installation
To set up the environment, use the provided environment.yml file.

## Create and Activate the Environment
conda env create -f environment.yml

conda activate time_prediction_env


## Results
In real-time prediction, users can select a *service name, and the system predicts the waiting time in real-time. The model achieves **high accuracy and fast inference* by leveraging optimized pre-processing and caching mechanisms.



