
# Wind Power Forecasting using ANN and RNN with a Cascading Approach

## Overview
This repository contains the code and resources for forecasting wind power potential using a **Cascading Approach** with **Artificial Neural Network (ANN)** and **Recurrent Neural Network (RNN)** models. This novel cascading method improves prediction accuracy compared to traditional approaches. The project focuses on predicting wind speed and estimating Wind Power Density (WPD) in the Anantapur region, leveraging meteorological data.

## Problem Statement
Wind energy is a vital renewable resource, and accurate wind speed predictions are crucial for optimizing wind farm operations. This project introduces a **Cascading Workflow** that enhances prediction accuracy by combining the outputs of different models in a sequence. The cascading approach is compared against traditional methods to demonstrate its superior performance in scheduling turbine maintenance and improving power output predictions.

## Dataset
The data has been collected from European data center at 10 meter level.
The dataset used for this study includes the following meteorological variables:
- **Temperature**
- **Soil Temperature**
- **Solar Radiation**
- **Pressure**
- **Eastward Wind (u10)**
- **Northward Wind (v10)**
- **Wind Speed** (target variable)

## Approach
This project leverages a unique **Cascading Approach** where multiple models are applied sequentially, refining predictions at each stage. Both **ANN** and **RNN** models are used in this cascading setup to predict wind speed over a 3-hour, 6-hour, 12-hour, 24-hour lead time . Various case studies were conducted to compare the performance of these models, with a focus on key statistical metrics, such as:
- **Mean Absolute Error (MAE)**
- **Root Mean Square Error (RMSE)**
- **Index Of Agreement (IOA)**

The cascading method outperformed traditional models in terms of accuracy and prediction robustness.

## Results
The cascading approach provided the best results, with low MAE and RMSE, proving the effectiveness of this novel method in wind speed forecasting. The approach is ideal for applications in estimating wind power potential, scheduling turbine maintenance, and improving the overall efficiency of wind farms.

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/NihaalChowdary/wind-power-forecasting.git

## Reslts

