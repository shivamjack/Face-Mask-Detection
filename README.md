# Face-Mask-Detection

## Problem Statement
To detect whether or not a person is wearing a face-mask by using Convolution Neural Networks and OpenCV

## Dataset

This dataset contains a data folder which contains 2 subdirectories namely

- without_mask 
- with mask 

## Image Preprocessing

All the images are not of the same size, and neural networks often expect images that are standardized; a fixed size. Therefore, the following preprocessing steps are performed:

    Gray scaling
    Normalize
    Resize
    Reshape

## Model Building and Training :

    Here a basic model is built using CNN and Keras library.
    Model is first trained on both with and without masks images.
    Then model is tested on sample test data. Whichever model is giving the good accuracy that model is saved for further use.

