# Amazon Stock Forecast Model with PyTorch LSTM

This repository contains code for building and training a Long Short-Term Memory (LSTM) neural network model using PyTorch to forecast the stock prices of Amazon (AMZN). The model utilizes historical stock price data to predict future price movements.

## Dataset

The model is trained on historical Amazon stock price data. The dataset includes features such as opening price, closing price, highest price, lowest price, and trading volume.

## Model Architecture

The LSTM model architecture consists of:
- Input layer: Receives input features - closing price.
- LSTM layers: Stacked LSTM layers to capture temporal dependencies in the input sequence.
- Fully connected (FC) layer: A linear layer to output the predicted stock price.

## Requirements

- Python 3.x
- PyTorch
- Pandas
- NumPy
- Matplotlib
- scitkit-learn
  
Installation:

To install the required dependencies, run the following command:

```bash
pip install -r requirements.txt
```
