# SEM Image-Based Salting-Out Morphology Prediction Using CNN

## Project Overview

This project demonstrates a basic deep learning workflow for classifying scanning electron microscopy (SEM) images using a convolutional neural network (CNN). The goal is to practice how SEM images can be used as input data for an AI model to identify different hydrogel morphology groups related to salting-out behavior.

The model was developed using Google Colab, TensorFlow/Keras, and Python image-processing tools.

## Project Aim

The aim of this project is to build a simple CNN-based image classification model that can analyze SEM images and predict the most similar morphology class based on the training dataset.

In this practice project, the model classifies SEM images into groups such as:

- MWCNT
- NaCl
- Self-healing hydrogel

In future work, the classification labels can be changed to salting-out severity levels, such as:

- Weak salting-out
- Moderate salting-out
- Strong salting-out

## Workflow

The project follows these steps:

1. Upload SEM images to Google Colab
2. Organize the images into labeled folders
3. Convert `.tif` SEM images into `.png` format
4. Load the image dataset using TensorFlow
5. Train a CNN model
6. Predict the class of a new SEM image
7. Display the output image with the predicted label and confidence score

## Dataset Structure

The image dataset was organized into class folders:

```text
FIBER_BIG/
├── MWCNT/
├── Nacl/
└── selfhealing/
