# Age and Gender Detection using UTKFace Dataset

## Overview
This project uses Convolutional Neural Networks (CNNs) based on the MobileNetV2 architecture to predict age and gender from facial images. The UTKFace dataset serves as the basis for training and evaluation. The model is capable of regression-based age prediction and can be used in applications like demographic analysis.

## Features
- Regression-based age prediction from facial images.
- Preprocessing steps such as resizing, normalization, and augmentation for robust model performance.
- Leveraging TensorFlow/Keras for deep learning model implementation.
- Includes EarlyStopping for efficient training.

## Dataset
The project uses the [UTKFace dataset](https://www.kaggle.com/datasets/jangedoo/utkface-dataset) from Kaggle, which contains facial images with labeled age and gender.

## Requirements
See `requirements.txt` for all dependencies.
## Results
The trained model achieved competitive accuracy in age regression tasks, with Mean Absolute Error (MAE) results visualized during training.
