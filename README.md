# traffic_signs_recognition
 Project is classifying traffic signs using a standard benchmark dataset. This project is valuable as it has direct applications in autonomous driving, a cutting-edge field. 
# Data set by Kaggle - GTSRB - German Traffic Sign Recognition Benchmark  
https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign?select=Test
# Overview of project 
This project is a deep learning-based system for recognizing German traffic signs using the GTSRB (German Traffic Sign Recognition Benchmark) dataset. 

# What it does
Takes an image of a traffic sign as input

Identifies which type of traffic sign it is (out of 43 possible classes)

Shows the predicted sign type with its name (like "Stop", "Yield", speed limits etc.)

# Key Components


# Model - A Convolutional Neural Network (CNN) with

Convolutional layers for feature extraction

Max pooling layers

Dense layers for classification

Dropout to prevent overfitting


# User Interface - Built with Gradio for easy testing - users can upload images and get instant predictions

# Technical Highlights
Image preprocessing (resizing to 32x32 pixels, normalization)

One-hot encoding for multi-class classification

70 epochs of training with Adam optimizer

Real-time prediction capability

The system could be useful for autonomous vehicles, driver assistance systems, or traffic monitoring applications where automatic sign recognition is needed.

# Results



