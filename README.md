# Sign-Language-Detection

## Description
This repository contains a machine learning model capable of recognizing various sign language gestures based on the Sign Language MNIST dataset. The model utilizes a Convolutional Neural Network (CNN) architecture to extract relevant features from image data and classify them into corresponding sign language categories.

## Dataset
[Sign Language MNIST](https://www.kaggle.com/datasets/datamunge/sign-language-mnist): A dataset consisting of 27,455 grayscale images, each representing a single handwritten sign language character. The images are normalized to a size of 28x28 pixels.

## Training:
- Training Data: `sign_mnist_train.csv`
- Validation Data: `sign_mnist_test.csv`
- Loss Function: `sparse_categorical_crossentropy` is used to measure the difference between predicted and actual class labels.
- Optimizer: `Adam` optimizer is employed to update model weights during training.

## Future Work:
- Expand the dataset to include a wider range of sign language gestures and dialects.
- Explore techniques to improve the model's performance in challenging lighting conditions and with complex backgrounds.
- Investigate the use of generative adversarial networks (GANs) to augment the training dataset.
- Make a real-time sign detection model.
