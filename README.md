# Stock_predict_TW
A prediction of Taiwan stock

This is a prediction of the TW stock, I modified the model and hyperparameters for a proper state of TW.

ENV:

Python

TensorFlow

yfinance

matplotlib

else...

below is the library I used

import os
import numpy as np
import random
import secrets
import pandas as pd
import tensorflow as tf
import yfinance as yf
import tensorflow_addons as tfa
import matplotlib.pyplot as plt
from tensorflow.python.keras import Sequential
from tensorflow.python.keras.layers import Dropout, Dense, LSTM
from sklearn.preprocessing import MinMaxScaler
from datetime import date
from datetime import datetime
from datetime import timedelta
from absl import app

1. choose which stock you want to predict(I use 2609.TW as example)
2. change the name in code("STOCK_TICKER"  hint : plz add ".TW" if you want to predict TW stock)
3. change the date
4. run the .ipynb
5. get the prediction
