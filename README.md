# Multi-Tasking Convolutional Neural Network for Emotion and Gender Detection

![Project Banner](![Uploading image.png…]())

## Overview

This project focuses on developing a multi-tasking Convolutional Neural Network (CNN) for simultaneous emotion and gender detection. The model is designed to efficiently identify both the emotional state and gender of subjects in images.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Architecture](#model-architecture)
- [Training and Evaluation](#training-and-evaluation)
- [Real-Time Application](#real-time-application)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Emotion and gender detection are crucial tasks in computer vision, with applications ranging from human-computer interaction to surveillance systems. This project integrates these two tasks into a single, efficient CNN model, leveraging a custom dataset and advanced preprocessing techniques.

## Dataset

To facilitate training and testing, a custom dataset was curated for emotion and gender detection. Images were sourced from Google and pre-processed using OpenCV 2. The dataset includes a diverse range of subjects, ensuring robustness and generalizability.

## Preprocessing

The preprocessing steps included:
- **Resizing**: Ensuring all images have a consistent size.
- **Normalization**: Scaling pixel values to a range of [0, 1].
- **Augmentation**: Applying random transformations to increase dataset diversity.

The dataset was meticulously split into training, testing, and validation sets to ensure proper model evaluation.

## Model Architecture

The CNN architecture was developed to cater to both emotion and gender detection tasks. Key features of the model include:
- **Convolutional Layers**: For feature extraction.
- **Pooling Layers**: For dimensionality reduction.
- **Fully Connected Layers**: For classification.

## Training and Evaluation

Label conversion was carried out to transform categorical labels into one-hot encoded vectors, facilitating the training process. The model was trained on the curated dataset, and various metrics were used to evaluate its performance on both emotion and gender detection tasks.

## Real-Time Application

The model's real-world applicability was demonstrated by integrating it with a live camera, enabling real-time identification of emotions and gender from a video feed. This implementation showcases the versatility and practicality of the developed multi-tasking CNN in a dynamic environment.

## Results

The model achieved impressive accuracy on both tasks, demonstrating its effectiveness in real-world scenarios. Detailed results and performance metrics are documented in the project notebook.

## Installation

To run this project locally, ensure you have the following dependencies installed:

```bash
pip install tensorflow opencv-python numpy matplotlib
