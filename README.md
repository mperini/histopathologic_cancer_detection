# Histopathologic Cancer Detection
This repository contains kernels and other files used for the Kaggle competition [Histopathologic Cancer Detection](https://www.kaggle.com/c/histopathologic-cancer-detection).

### CNN Classifier.ipynb
In this notebook a Convolutional Neural Network (CNN) is built using Keras (Tensorflow backend) and trained on the dataset. Data augmentation is performed using standard transformations implemented in Keras' ImageDataGenerator class.

### Transfer learning.ipynb
In this notebook the model is built using Keras (Tensorflow backend) starting from a pre-trained network, whose weights are fine-tuned to adapt to the specific classification problem. Data augmentation is performed using the imgaug library ( https://github.com/aleju/imgaug ). Test-Time Augmentation is also used to improve the classification accuracy.
