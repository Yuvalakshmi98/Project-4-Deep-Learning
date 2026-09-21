# Project-4-Deep-Learning
Image classification is one of the most widely used applications of Deep Learning in Computer Vision. Businesses use image classification to automate quality inspection, object recognition, medical diagnosis, retail product categorization, security surveillance, and many other real-world applications.
# CIFAR-10 Image Classification

## Overview

Image classification on the **CIFAR-10 dataset** using:

* CNN
* Transfer Learning with MobileNetV2

## Dataset

* 60,000 images
* 10 classes
* 50,000 training and 10,000 testing images
* Image size: 32×32×3

## CNN Results

**Test Accuracy: 70%**

| Precision | Recall | F1-Score |
| --------: | -----: | -------: |
|      0.69 |   0.70 |     0.69 |

## MobileNetV2 Results

**Test Accuracy: 81%**

| Precision | Recall | F1-Score |
| --------: | -----: | -------: |
|      0.81 |   0.81 |     0.81 |

## Model Comparison

| Model       | Accuracy |
| ----------- | -------: |
| CNN         |      70% |
| MobileNetV2 |      81% |

## Evaluation

* Accuracy and Loss
* Confusion Matrix
* Classification Report
* Prediction Visualization

## Technologies

Python, TensorFlow/Keras, NumPy, Matplotlib, Scikit-learn, Seaborn

## Conclusion

MobileNetV2 achieved **81% accuracy**, compared with **70%** for the CNN model.
