# Pats_Bills_Predict

Patriots Bills Series Rivalary

Resources
This program uses keras to constuct the neural network

numpy, scipy and pandas are used to structure the data

matplotlib is used to plot the results

All data is sourced from Pro Football Reference

Neural Network Training

Spreasdseet contains the folllowing

Games scores from each Patriots - Bills games all time pro-football-reference.com

Features that have been shown relevance in predicting game outcome.

Total yardage differential

Time of possession differential (in seconds)

Home or away


# Imports
import pandas as pd

from pathlib import Path

import tensorflow as tf

from sklearn.model_selection import train_test_split

from sklearn import preprocessing

from sklearn.preprocessing import StandardScaler

from sklearn.preprocessing import OneHotEncoder

import warnings

warnings.filterwarnings('ignore')

 # Import Sequential and Dense from Tensorflow Keras
 
from tensorflow.keras.models import Sequential

from tensorflow.keras.layers import Dense
