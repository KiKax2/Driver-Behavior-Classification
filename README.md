# Driver Behavior Image Classification

## Project Overview

This project aims to classify driver behaviors from images using deep learning techniques. By analyzing static images, the system identifies specific behaviors such as: Dangerous Driving, Safe Driving and Sleepy Driving.

The primary objective is to enhance road safety by accurately detecting potentially dangerous behaviors from images.

## Features

- **Image Classification**: Utilizes a Convolutional Neural Network (CNN) to classify images into predefined behavior categories.
- **Model Training**: Implements data preprocessing, model training, and evaluation pipelines.
- **Visualization**: Includes tools to visualize training progress and classification results.

## Dataset

The model is trained on the [Driver Inattention Detection Dataset](https://www.kaggle.com/datasets/zeyad1mashhour/driver-inattention-detection-dataset), which includes labeled images of various driver behaviors. The dataset comprises multiple classes, including:

- **DangerousDriving**
- **Distracted**
- **Drinking**
- **SafeDriving**
- **SleepyDriving**
- **Yawn**

## Model Architecture

The classification model is built using TensorFlow and Keras, featuring:

- **Convolutional Layers**: Extract spatial features from input images.
- **Max-Pooling Layers**: Reduce spatial dimensions and retain essential information.
- **Fully Connected Layers**: Perform classification based on extracted features.
- **Dropout Layers**: Prevent overfitting during training.

## Setup and Installation

To set up the project, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/driver-behavior-classification.git
   cd driver-behavior-classification
