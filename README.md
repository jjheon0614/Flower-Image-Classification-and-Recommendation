# Flower-Image-Classification-and-Recommendation

## Project Overview

This project focuses on classifying images of flowers into predefined categories and recommending similar flower images based on input images. The implementation is designed for an e-commerce flower shop to help users navigate and identify flower types using machine learning techniques.

## Tasks

1. Image Classification: Identify the flower type from the given image. The dataset contains 8 flower categories:

- Baby
- Calimero
- Chrysanthemum
- Hydrangeas
- Lisianthus
- Pingpong
- Rosy
- Tana

2. Image Recommendation: Suggest 10 most similar flower images based on a given input image.

## Model Selection and Training

### Image Classification Model

- Utilized ResNet-18 due to its interpretability and efficiency in training.
- Implemented in PyTorch for model training.
- Used cross-entropy loss and Adam optimizer.
- Achieved accuracy of 60-80% depending on the class.

### Image Recommendation Model

- Used VGG16 for feature extraction.
- Implemented in TensorFlow + Keras.
- Applied cosine similarity for recommending similar images
