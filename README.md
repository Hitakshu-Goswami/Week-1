Waste Management Using CNN

Overview

This project leverages a Convolutional Neural Network (CNN) to classify waste into Organic and Recyclable categories. The goal is to streamline waste sorting and management using cutting-edge machine learning techniques. Built with TensorFlow, OpenCV, and Python, this project showcases the potential of AI in environmental sustainability.
Features

Image Preprocessing: Utilizes OpenCV for image loading, resizing, and color adjustments.

Data Augmentation: Improves model generalization using TensorFlow's ImageDataGenerator.

CNN Model Architecture: Designed with Conv2D, MaxPooling, Dropout, BatchNormalization, and Dense layers for optimal performance.

Visualization: Includes pie charts and training-validation plots for better understanding of the data and training progress.

Evaluation Metrics: Provides accuracy, loss, confusion matrix, and classification reports.
Technologies Used

Python: Core programming language.

TensorFlow/Keras: For building and training the CNN.

OpenCV: For image processing.

Matplotlib: For data visualization.

Pandas: For handling and analyzing the dataset.
Prerequisites

Python 3.8 or above.

Libraries:

TensorFlow

OpenCV

NumPy

Pandas

Matplotlib

tqdm

Model Architecture

The CNN consists of:

Convolutional Layers: Extract spatial features from images.

MaxPooling Layers: Reduce spatial dimensions to prevent overfitting.

BatchNormalization: Normalize intermediate layers to improve stability.

Dropout Layers: Regularization to prevent overfitting.

Dense Layers: Fully connected layers for final classification.

Training the Model
Results

Accuracy: Achieved high training and validation accuracy.

Visualization:

Pie chart showing data distribution.

Accuracy and loss plots during training.

Evaluation:

Confusion matrix and classification report for performance insights.
Improvements Made

Preprocessing Enhancements: Normalized data using ImageDataGenerator for better convergence.

Optimized CNN Architecture: Added Dropout and BatchNormalization layers to prevent overfitting.

Detailed Evaluation: Included confusion matrix and classification report for deeper analysis.

Scalability: Modularized code for easy extension to other waste categories.

