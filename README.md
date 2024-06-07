# Image Classification with VGG16 Architecture

This project implements an image classification model using the VGG16 architecture to classify images of cats and dogs. The model is trained using Keras and TensorFlow, and the dataset is loaded from a specified directory.

## Project Overview
- [x] This project aims to build and train a convolutional neural network (CNN) based on the VGG16 architecture for binary image classification. The model classifies images into two categories: cats and dogs.
## Dataset
- [x] The dataset consists of images of cats and dogs organized into training and test sets. The dataset should be placed in two zip files named training_set.zip and test_set.zip which contain folders for each class (cats and dogs).

## Model Architecture
- [X] The model follows the VGG16 architecture with several convolutional and max-pooling layers, followed by fully connected layers. The final layer uses a sigmoid activation function to output probabilities for the two classes.

## Training
- [X] The model is trained using the Adam optimizer with a learning rate of 0.0001 and binary cross-entropy loss. The training process includes checkpoints to save the best model based on validation accuracy and early stopping to prevent overfitting.

## Evaluation
-[X] After training, the model's performance is evaluated on the test set. The accuracy and loss for both training and validation sets are plotted to visualize the training process.
