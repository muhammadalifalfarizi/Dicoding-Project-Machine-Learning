# Rock-Paper-Scissors Image Classification

This repository contains code for training a convolutional neural network (CNN) model to classify
images of rock, paper, and scissors using TensorFlow.

## Dataset

The dataset used for training and validation is the "Rock-Paper-Scissors" dataset, which can be downloaded from [here](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip). The dataset consists of images of hands showing rock, paper, or scissors gestures.

## Image Prediction

After training the model, you can use it to predict the class of an uploaded image of rock, paper, or scissors.
The code provides an option to upload an image using the `files.upload()` function.
Once the image is uploaded, the model predicts its class and displays the result.
