# Rock-Paper-Scissors Image Classification Project

This project demonstrates the creation of an image classification model using deep learning to distinguish between images of rock, paper, and scissors.

![Rock-Paper-Scissors](https://www.science.org/do/10.1126/science.aac4663/abs/sn-rockpaper.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Data Preparation](#data-preparation)
- [Model Development](#model-development)
- [Model Training](#model-training)
- [Predict Custom Images](#predict-custom-images)
- [Results](#results)
- [Credits](#credits)
- [License](#license)

## Introduction
Image classification is a fundamental task in computer vision, and this project is a practical example of how to build an image classification model using a convolutional neural network (CNN). The primary goal is to classify hand signs of rock, paper, and scissors in images.

## Project Overview
This project consists of several key steps:
1. **Data Collection:** Obtaining a dataset of rock-paper-scissors images, which is used for training and validation.
2. **Data Preparation:** Cleaning and organizing the dataset, creating training and validation sets, and applying data augmentation to enhance model performance.
3. **Model Development:** A CNN model is constructed using TensorFlow and Keras to learn and classify the images.
4. **Model Training:** The model is trained on the augmented dataset to achieve high accuracy.
5. **Predict Custom Images:** Users can upload their own rock, paper, or scissors images and see how well the model classifies them.

## Requirements
To run this project, you will need the following software and libraries:
- Python 3
- TensorFlow
- Keras
- Numpy
- Matplotlib
- Requests
- Jupyter Notebook (optional)

## Getting Started
1. Clone or download this project repository to your local machine.
2. Install the required libraries mentioned in the `requirements.txt` file.
3. Open the provided Jupyter Notebook or Python script to follow along with the project steps.

## Data Preparation
The project includes a dataset of rock-paper-scissors images. To enhance the dataset and model performance, we apply data augmentation techniques. These techniques include rotation, resizing, and flipping of images to provide a variety of training data.

## Model Development
We create a CNN model using TensorFlow and Keras. The model architecture includes convolutional layers, max-pooling layers, and fully connected layers.

## Model Training
The model is trained on the augmented dataset with the goal of achieving a high level of accuracy. The training process is detailed in the project script.

## Predict Custom Images
In the provided notebook or script, you can upload your own rock, paper, or scissors images. The model will predict and classify them, allowing you to test its performance on custom data.

## Results
The project's success is evaluated based on the final validation accuracy. Model's final validation accuracy: 90.00%.

## Credits
This project was developed as part of the Dicoding Academy's "Belajar Machine Learning untuk Pemula" class – a comprehensive course on introductory machine learning. Special thanks to Dicoding Academy for providing valuable resources, guidance, and a platform for learning.

Course: [Belajar Machine Learning untuk Pemula](https://www.dicoding.com/academies/184)

Instructor: [Dicoding Academy](https://www.dicoding.com/)

Completion Date: 15/10/2023
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
