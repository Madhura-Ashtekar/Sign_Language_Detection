# Sign_Language_Detection

This project implements a Convolutional Neural Network (CNN) to detect and classify sign language digits (0-9) from images.
Features

Uses Keras with TensorFlow backend

Implements data augmentation for improved model generalization
Achieves high accuracy on test set (97.45%)
Includes example predictions on sample images

Dataset

The project uses the Sign Language Digits Dataset, which contains images of hand gestures representing digits 0-9 in sign language.

Model Architecture

3 Convolutional layers with MaxPooling and Dropout
Flatten layer
2 Dense layers
Output layer with 10 units (one for each digit)

Results

The model achieves 97.45% accuracy on the test set and successfully classifies all example images.

Future Work

Expand dataset to include more sign language symbols
Implement real-time detection using webcam input
Deploy model as a web application or mobile app
