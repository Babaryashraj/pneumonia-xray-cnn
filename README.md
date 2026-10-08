# Chest X-Ray Pneumonia Classification using CNN

## Overview

This project uses a Convolutional Neural Network (CNN) to classify chest X-ray images into two classes:

- NORMAL
- PNEUMONIA

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- Google Colab

## Dataset

The dataset contains:

- Training images: 148
  - NORMAL: 74
  - PNEUMONIA: 74

- Testing images: 40
  - NORMAL: 20
  - PNEUMONIA: 20

20% of the training data was used for validation.

## Model

The CNN contains:

- Rescaling layer
- Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layer
- Dropout layer
- Softmax output layer

## Features

- Image preprocessing
- CNN model training
- Validation
- Early stopping
- Test evaluation
- Confusion matrix
- Classification report
- Single image prediction

## Results

The model achieved 100% accuracy on the provided 40-image test set.

Because the dataset is small, this result should not be considered representative of real-world clinical performance.

## How to Run

Open the notebook:

`Pneumonia_XRay_CNN.ipynb`

in Google Colab and run the cells sequentially.

## Disclaimer

This project is for educational and research purposes only. It is not a medical diagnostic system.
