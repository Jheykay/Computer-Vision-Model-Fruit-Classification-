This a  Convolutional Neural Network (CNN) model to classify images of fruits into three 
categories: strawberries, pomegranates, and peaches. 
This is a CNN model also trained with a pretrained model(INCEPTION) that can accurately classify fruit images into one of the three specified categories.
Libraries imported
import pandas as pd
import pandas as np
#regular expression for identifying pattern
import re
#OS library for operating system
import os
from tensorflow.keras.applications import MobileNetV2
from tensorflow.keras.preprocessing.image import ImageDataGenerator
from tensorflow.keras.layers import GlobalAveragePooling2D, Dense
from tensorflow.keras.models import Model
from tensorflow.keras.callbacks import EarlyStopping
