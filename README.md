# Farm Expert - Plant Disease Detection using Deep Learning CNN

This repository provides the code and instructions required to implement a plant disease detection system using Deep Learning, specifically Convolutional Neural Networks (CNN). The system analyzes images of plant leaves to identify potential diseases, helping farmers and agricultural experts monitor plant health.

## Overview

The goal of this project is to create an automated system that can detect diseases in plants by analyzing images of their leaves. This is achieved using Convolutional Neural Networks (CNNs), a class of deep learning algorithms commonly used for image classification tasks.

The project involves:

1. Preprocessing plant leaf images for training.
2. Using CNN to classify the plant images into categories (healthy or diseased).
3. Evaluating the model's performance using metrics like accuracy, precision, recall, and F1-score.
4. Visualizing the model's predictions to provide insights.

## Features

- **Image Classification:** Classifies plant leaf images into healthy or diseased categories.
- **Model Training:** Uses CNNs for training on labeled image datasets.
- **Evaluation Metrics:** Evaluates model performance with accuracy, precision, recall, and F1-score.
- **Visualization:** Provides visual outputs to show predictions and model performance.

## Prerequisites

Before running the code, ensure you have the following software installed:

- Python 3.x
- TensorFlow (for model training)
- Keras (for deep learning framework)
- OpenCV (for image processing)
- Matplotlib (for data visualization)
- NumPy (for numerical computations)
- Scikit-learn (for model evaluation)

### Installing Dependencies

You can install all the required libraries using pip. Create a virtual environment, activate it, and then run the following command to install the necessary packages:

```bash
pip install -r requirements.txt
