# Medical Image Analysis for predicting Pneumonia

## Overview
This project focuses on predicting pneumonia in chest X-ray images using a TinyVGG (Tiny VGGNet) Convolutional Neural Network (CNN). The TinyVGG CNN is a lightweight variant of the VGGNet architecture, designed for efficient inference on resource-constrained devices while maintaining high predictive accuracy. The model is trained on a dataset of labeled chest X-ray images with pneumonia and normal cases. The primary goal is to create a robust and accurate pneumonia detection system for medical imaging applications.

## Workflow
### Data Collection: 
Obtain a dataset of chest X-ray images labeled with pneumonia and normal classes.

### Data Pre-processing:
Resize images to a consistent resolution suitable for model input.
Normalize pixel values to a standardized range (e.g., 0 to 1).
Split the dataset into training, validation, and test sets for model training and evaluation.

### Data Augmentation:
Apply data augmentation techniques such as rotation, flipping, and zooming to enhance the diversity of the training dataset and improve model generalization.
Model Training: Train the TinyVGG CNN model using the augmented training dataset. Use techniques like transfer learning if applicable for better performance.

### Model Evaluation: 
Evaluate the trained model's performance on the validation dataset to fine-tune hyperparameters and monitor training progress.

### Model Testing: 
Test the final trained model on an unseen test dataset to assess its generalization and predictive accuracy.
