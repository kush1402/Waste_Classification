WASTE CLASSIFICATION
This repository contains code to classify waste into organic or recyclable.

We used a Deep Learning Keras model with 6 Convolutional Layers and 2 Dense Layers to achieve a 91% test accuracy. use_model function can be used to predict on new data.

DATASET

We trained the model with 22564 images of which 12565 images were of oraganic items and 9999 images were of recyclable items. For the test set we had 1401 images for oragnic items and 1112 images of recyclable items making a total of 2513 items.

The dataset is available in kaggle. The link is available below
https://www.kaggle.com/techsash/waste-classification-data

DEPENDENCIES
Keras
Tensorflow
open-cv
PIL
matplotlib
