# Handwritten Digit Recognition Using CNN

## Project Overview

This project implements a handwritten digit recognition system using a Convolutional Neural Network (CNN) and the MNIST dataset. The system is designed to recognize handwritten digits from 0 to 9.

## Problem Description

The goal of this project is to build a deep learning model that can accurately classify handwritten digit images into one of ten classes, from 0 to 9.

## Dataset

The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits. Each image is grayscale and has a size of 28 × 28 pixels.

## Model

A Convolutional Neural Network (CNN) was used for image classification. The model includes convolutional layers, max pooling layers, and dense layers.

## Project Workflow

1. Load the MNIST dataset.
2. Preprocess and normalize the images.
3. Build the CNN model.
4. Train the model.
5. Evaluate the model on the test dataset.
6. Analyze the results using a classification report and confusion matrix.
7. Test the model using an interactive drawing interface.

## Evaluation

The model was evaluated using test accuracy, classification report, and confusion matrix.

## How to Run the Project

1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. The model will be trained and evaluated on the MNIST dataset.
4. Use the Interactive Digit Recognition section to draw a handwritten digit.
5. Click Predict to get the model prediction.

## Workflow / System Diagram

**Input Image**  
↓  
**Preprocessing**  
Resize → Normalize → Reshape  
↓  
**CNN Model**  
Convolution → Max Pooling → Dense  
↓  
**Prediction**  
↓  
**Predicted Digit**

## Results

The CNN model achieved a test accuracy of approximately 98.64% on the MNIST test dataset.

The classification report shows Precision, Recall, and F1-score across all ten digit classes. The model was also evaluated using a Confusion Matrix to analyze its classification performance.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Future Improvements

The system could be further improved by:
- Allowing users to upload handwritten digit images.
- Improving the user interface.
- Testing the model with more diverse handwriting styles.
- Exploring additional CNN architectures.

## Relevant Chapters from Deep Learning with Python

- Chapter 8: Image classification
- 
 ## SDAIA Academy GitHub Repository Link
https://github.com/mudawi860/handwritten-digit-recognition
