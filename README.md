
# MNIST Digit Denoising with KNN Classifier

This project demonstrates the process of adding noise to the MNIST dataset and then training a K-Nearest Neighbors (KNN) classifier to remove the noise and predict the original digit.

## Overview

The MNIST dataset is a well-known dataset of handwritten digits. In this project, we:
- Add random noise to the images in the MNIST dataset.
- Train a KNN classifier to denoise the images and predict the original digits.

## Dataset

The MNIST dataset contains 70,000 images of handwritten digits, each 28x28 pixels. The images are grayscale, and each pixel is represented by an integer from 0 to 255.

## Steps

1. **Load MNIST Dataset**:
   - Load the MNIST dataset using `fetch_openml` from `sklearn.datasets`.

2. **Add Noise to the Dataset**:
   - Add random noise to the training and test images to create noisy versions of the dataset.
   - Noise is added by generating random integers between 0 and 100 and adding them to the original pixel values.

3. **Train a KNN Classifier**:
   - Train a KNN classifier on the noisy dataset to predict the original digits.

4. **Evaluate the Classifier**:
   - Evaluate the performance of the classifier using accuracy and confusion matrix.

![enter image description here](https://i.ibb.co/jJG799z/Screenshot-2024-06-04-at-9-31-44-PM.png)

![enter image description here](https://i.ibb.co/B3972K0/Screenshot-2024-06-04-at-9-31-55-PM.png)



![enter image description here](https://i.ibb.co/WBDjzzM/Screenshot-2024-06-04-at-9-32-06-PM.png)
