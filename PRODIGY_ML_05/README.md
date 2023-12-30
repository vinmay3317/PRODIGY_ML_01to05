# Food Recognition and Calorie Estimation Model

## Overview
This project aims to develop a model that can accurately recognize food items from images and estimate their calorie content. The objective is to provide users with a tool for tracking their dietary intake and making informed food choices.

## Dataset
The model is trained on the Food-101 dataset, which contains images of 101 different food categories. The dataset includes a variety of food items, making it suitable for training a diverse food recognition model. You can take dataset from here,-https://www.kaggle.com/dansbecker/food-101 

## Model Development
Neural Network Architecture
The model utilizes the ResNet50 architecture, a deep convolutional neural network known for its effectiveness in image recognition tasks. The network is modified to include additional layers for fine-tuning to the specific food recognition and calorie estimation objectives.

## Training
The model is trained on the prepared dataset using transfer learning. The training process includes data augmentation techniques such as rescaling, shearing, zooming, and horizontal flipping to enhance the model's ability to generalize to different food images.

## Model Evaluation
The performance of the model is evaluated on a separate test set. Metrics such as accuracy and loss are monitored to assess the model's ability to recognize food items and estimate their calorie content.

## Results and Visualization
Plots depicting the training and validation accuracy as well as loss are provided to visualize the learning progress of the model. Additionally, sample predictions on test images are displayed to showcase the model's effectiveness in recognizing and categorizing food items.

## Usage

### Download the Dataset:
Kaggle API credentials are required for downloading the Food-101 dataset. Follow the provided code to set up the Kaggle API and download the dataset.

### Data Preparation:
The dataset is organized into train and test sets, and a subset of food classes is selected for focused training.

### Model Training:
The ResNet50-based model is trained on the prepared dataset using transfer learning techniques.

### Model Evaluation:
The trained model is evaluated on a test set to assess its accuracy in recognizing food items and estimating their calorie content.

### Visualization:
Plots are generated to visualize the training and validation accuracy as well as loss over epochs.

### Inference:
The model can be used for making predictions on new images to recognize food items and estimate their calorie content.

### Additional Notes
The model is saved after training, and the best-performing model is stored for future use.
Users can modify the code to include additional food classes or experiment with different neural network architectures.

## Author
Vinmay Tondle.
