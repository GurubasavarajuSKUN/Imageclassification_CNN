# Dog-Cat Image Classification with TensorFlow and CNN

## Overview

This project demonstrates image classification using a Convolutional Neural Network (CNN) implemented with TensorFlow. The primary objective is to classify images as either "dog" or "cat" based on a custom dataset created for this purpose.

## Features

- **Custom Dataset:** We have curated a custom dataset of labeled dog and cat images for model training and evaluation.

- **CNN Architecture:** The project employs a deep CNN model built with TensorFlow, capable of learning intricate image features.

- **Training and Evaluation:** The model undergoes training using the custom dataset and is evaluated for accuracy and performance.

## Prerequisites

Before running this project, ensure that you have the following dependencies installed:

- Python 3.x
- TensorFlow
- Required Python packages (specified in `requirements.txt`)

## Dataset Preparation

- Assemble a dataset of labeled dog and cat images. Organize it into training and testing subsets.

- Ensure a balanced dataset with an equal number of dog and cat images for optimal model performance.

## Training

1. Clone this repository to your local machine using `git clone`.

2. Organize your custom dataset into the appropriate directories (e.g., `train/dog`, `train/cat`, `test/dog`, `test/cat`).

3. Install the required Python packages using `pip install -r requirements.txt`.

4. Initiate the training process by running the following command:

   ```bash
   python train.py

