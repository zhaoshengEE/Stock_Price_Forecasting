# Stock Price Forecasting

## Authors
Menghong Huang, &nbsp; Zhaosheng Li

## Table of contents

- [Description](#Description)
- [ML models](#ML-models)
- [Data in this project](#Data-in-this-project)
- [Forecasts](#Forecasts)
- [Evaluation metrics](#Evaluation-metrics)
- [Files in this repo](#Files-in-this-repo)
- [Results](#Results)
- [Dependencies for this project](#Dependencies-for-this-project)
- [Download the code](#Download-the-code)

## Description
This project implements various machine learning (ML) models to forecast the stock price of an
American gaming merchandise retailer, namely, _GameStop Corporation_. There are two types of forecasts in this project, which are the next-day forecast and the 30-day forecast. 
The objective of this project is to compare the performance of each model on those two kinds of forecasts, and the comparison is based on several evaluation metrics.

## ML models

Here are the ML models used in this project:

- Linear regression (LR)
- Support vector regression (SVR)
- Backpropagation neural network (BPNN)
- Simple recurrent neural network (RNN)
- Long short-term memory (LSTM) network
- Gated recurrent units (GRU) network

## Data in this project


## Forecasts

### Next-day forecast

![Next-day_forecast.png](img/Next-day_forecast.png)

&nbsp;

### 30-day forecast

![30-day_forecast.png](img/30-day_forecast.png)


## Evaluation metrics



## Files in this repo

This GitHub repo contains the following folders or files

+ `img` folder contains the images of the training results, neural network structures, and test results

+ `model` folder contains the all the trained ANN and CNN models used in this project

+ `ANN_vs_CNN.ipynb` is the code for comparing the performance of ANN and CNN on classifying the modulation schemes of the RF signals in dataset

+ `ANN_using_PCA.ipynb` and `CNN_using_PCA.ipynb` are the code for applying PCA on the original dataset and observing the performance of ANN and CNN versus different values of dimension reduction 

+ `ANN.ipynb` and `CNN.ipynb` are the prototype of ANN and CNN models at the beginning stage of this project

+ `Project_Report.pdf` is the report of this project, which contains specific technical details and in-depth discussion

## Results

## Dependencies for this project

This project requires the following python modules:

```python
numpy  matplotlib.pyplot  pandas  sklearn  keras  seaborn  joblib
```

Please make sure you have all the modules installed before running the code. For installing these modules, one can use command `pip install` or `conda install`

## Download the code

```bash
git clone https://github.com/zhaoshengEE/Stock_Price_Forecasting.git
```


The GME price data is located in `Data` folder<br>
`Img` folder contains the graphs of prediction result on close price via each model<br>
The \*\_`Model` folders saved the trained models of each techniques respectively.
