# Dogs vs Cats Redux: Kernels Edition

This repository contains the code and resources for the "Dogs vs Cats Redux: Kernels Edition" competition on Kaggle.

## Competition Overview

The "Dogs vs Cats Redux: Kernels Edition" competition is a popular image classification challenge hosted on Kaggle. The goal is to develop an algorithm that can accurately classify images as either dogs or cats. Participants are provided with a large dataset of labeled images for training and a separate dataset for testing their models. The competition encourages the use of creative and innovative approaches to achieve high classification accuracy.

To learn more about the competition and participate, visit the [competition overview page](https://www.kaggle.com/competitions/dogs-vs-cats-redux-kernels-edition/overview).

## Repository Structure

- `data`: This directory contains the training and test datasets provided for the competition.
- `notebooks`: This directory includes Jupyter notebooks with code for data exploration, model training, and evaluation.
- `submissions`: Here, you can find sample submissions or final model predictions in the required format.
- `utils`: This directory contains utility scripts or functions that may be used in the notebooks.

## Getting Started

To get started with this repository, follow these steps:

In this competition, we explored various models and techniques to improve classification accuracy. Here are the models we experimented with:

1. **Convolutional Neural Network (CNN):**
   - Architecture: We utilized a deep CNN with multiple convolutional and pooling layers followed by fully connected layers.
   - Training: The model was trained on the provided dataset, including data augmentation techniques such as rotation, resizing, and horizontal flipping.
   - Results: The CNN achieved an accuracy of 85% on the validation set.

2. **Transfer Learning with Pretrained Models:**
   - Models: We experimented with pretrained models such as VGG16, ResNet50, and InceptionV3.
   - Fine-tuning: We fine-tuned the models on the competition dataset by freezing the initial layers and training the remaining layers.
   - Results: The best performing model was InceptionV3, which achieved an accuracy of 90% on the validation set.

## Result
The model was trained on 20000 images of dogs and cats, validated on the rest of the 5000 pictures, and ultimately achieved over 99% accuracy on the validation set.
