# SVM Image Classification: Cats vs Dogs
This project implements a Support Vector Machine (SVM) to classify images of cats and dogs.

## Overview
The program preprocesses and flattens the images, applies Principal Component Analysis (PCA) for dimensionality reduction, and utilizes the SVM algorithm for image classification. The dataset consists of 25,000 images, equally divided between cats and dogs.

## Program Highlights
#### Dataset Analysis: The training dataset is analyzed to determine the number of cat and dog images.

#### Image Preprocessing: Images are loaded, converted to grayscale, resized, and normalized.

#### Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the feature vectors.

#### Model Training: An SVM model is trained using the scikit-learn library. Grid search is used to find optimal hyperparameters.

#### Model Evaluation: The trained model is evaluated using accuracy, a confusion matrix, and a classification report on a test set.

#### Prediction: The model is used to predict whether an unseen image is of a cat or a dog. Probability scores for both classes are provided.

## Usage
-Install Dependencies:
pip install opencv-python pandas numpy scikit-learn scikit-image matplotlib

-Run the Program:
Execute the provided Jupyter Notebook svm_image_classification.ipynb in your preferred development environment.

-Follow Instructions:
The program guides you through loading the dataset, preprocessing images, applying PCA, training the SVM model, and making predictions.

## Files
svm_image_classification.ipynb: Jupyter Notebook containing the SVM image classification implementation.

train/: Directory containing the training images (cats and dogs).

test1/: Directory containing test images for prediction.

image_classifier_svm.sav: Saved SVM model artifact.

## Results
The trained SVM model achieves an accuracy of approximately 65.43% on the test set. Detailed evaluation metrics can be found in the classification report.

## Acknowledgments
The dataset used in this project is sourced from Kaggle.
Dataset = https://www.kaggle.com/c/dogs-vs-cats/data

## Author
Vinmay Tondle
