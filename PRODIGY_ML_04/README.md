# Hand Gesture Recognition Model

## Overview
This project aims to develop a hand gesture recognition model using image data for intuitive human-computer interaction and gesture-based control systems, you can refer data from https://www.kaggle.com/gti-upm/leapgestrecog here. The model is trained to accurately identify and classify different hand gestures.

## Requirements
Python 3.x
OpenCV
scikit-image
NumPy
Matplotlib
Keras
TensorFlow
scikit-learn
seaborn
Installation

To install the required dependencies, you can use the following command:

pip install opencv-python scikit-image numpy matplotlib keras tensorflow scikit-learn seaborn

### Data Preprocessing:

Images are resized to (50, 50) pixels.
Image data is shuffled and split into input data and labels.

### Data Visualization:

Display a sample of hand gesture images with their corresponding labels.

### Model Definition:

A convolutional neural network (CNN) is defined using Keras.
The model architecture includes convolutional layers, activation functions, max-pooling, dropout, and fully connected layers.

### Model Training:

The model is compiled with categorical crossentropy loss and RMSprop optimizer.
Training is performed using the training data, and validation is done on a separate test set.

### Model Evaluation:

Model performance is visualized with loss and accuracy plots.
Test accuracy is printed.

### Confusion Matrix:

A confusion matrix is generated to evaluate the classification performance.

## Results
The model achieves a certain accuracy on the test set, demonstrating its capability to recognize and classify hand gestures.

## Author
Vinmay Tondle.
