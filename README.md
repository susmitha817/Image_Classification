# Image_Classification
This project demonstrates an image classification pipeline using the CIFAR-10 dataset. A Convolutional Neural Network (CNN) is built with TensorFlow/Keras to classify images into ten predefined categories.

Features:
Dataset: CIFAR-10 dataset, comprising 60,000 images (32x32 pixels) categorized into ten classes.
Model Architecture:
Input layer for RGB images of size 32x32.
Three Conv2D layers with Batch Normalization, Max Pooling, and Dropout for regularization.
Fully connected layers for feature aggregation and final classification.
Training:
Optimizer: Adam.
Loss function: Sparse Categorical Crossentropy.
Metrics: Accuracy.
Results:
Training and validation accuracy are plotted for model evaluation.

Usage:
Train the model using the CIFAR-10 dataset.
Save predictions as a CSV file for submission or evaluation.
Visualize classification performance on random test samples.

Output:
CNN Model File: cnn_model.h5
Submission File: submission.csv containing the predicted labels.
Visualization: Test predictions are displayed alongside their actual labels.
