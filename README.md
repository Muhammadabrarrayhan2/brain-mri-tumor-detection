# brain-mri-tumor-detection
A deep learning project for classifying brain tumor MRI images (glioma, meningioma, pituitary, no tumor) using convolutional neural networks with TensorFlow.
## Project Overview

Brain tumors are abnormal cell growths in the brain that require early detection for effective treatment. In this project, a deep learning approach is used to classify MRI brain images into tumor categories using image processing and convolutional neural networks.

## Objectives

- Build a machine learning pipeline for MRI image classification
- Preprocess MRI datasets for deep learning
- Train a CNN model to classify brain tumors
- Evaluate model performance using classification metrics
- Provide a foundation for medical image analysis using AI

## Dataset

The dataset contains MRI brain images organized into different classes:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

Each class contains MRI scan images used for training and evaluation.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- OpenCV
- Google Colab

## Methodology

The pipeline includes:

1. Uploading and extracting the MRI dataset
2. Data preprocessing and normalization
3. Data augmentation using ImageDataGenerator
4. Training a Convolutional Neural Network
5. Model evaluation using confusion matrix and classification report
6. Saving the trained model for inference

## Results

The trained model is able to classify MRI images into tumor categories using convolutional neural networks. Performance is evaluated using validation accuracy and classification metrics.

## How to Run

1. Open the notebook in Google Colab
2. Upload the MRI dataset
3. Run all cells sequentially
4. Train the CNN model
5. Evaluate model performance
   
## Future Improvements

- Use transfer learning models such as MobileNetV2 or EfficientNet
- Deploy the model as a web application
- Improve dataset preprocessing and augmentation
- Build a real-time tumor classification dashboard

## Author

Muhammad Abrar Rayhan
7. Save the trained model

## Repository Structure
