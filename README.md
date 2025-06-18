# Human Face Expression Detection
A deep learning project that classifies human facial expressions—like happy, sad, angry, surprised, fear, disgust, and neutral—using a Convolutional Neural Network (CNN).

# Project Overview

This project aims to recognize facial emotions from static images using deep learning techniques. A CNN model is trained on a labeled facial expression dataset (e.g., FER2013) to classify emotions accurately. The goal is to develop a system that can interpret basic human emotions through facial cues, which can be useful in emotion-aware applications.

# Results & Findings

Achieved over 70% accuracy on validation data.

The model performed consistently well on distinct expressions such as happy, sad, and angry, demonstrating strong generalization across these categories.

Minor performance drops were noted in less visually distinct emotions like fear and disgust, which may benefit from additional training data or fine-tuning.

# Training Details

Model: Custom CNN with Conv2D, MaxPooling, Dropout, and Dense layers

Dataset: FER2013 (48x48 grayscale facial images)

Epochs: 30

Batch Size: 32

Optimizer: Adam

Loss Function: Categorical Crossentropy

Framework: TensorFlow / Keras

# Sample Detection
Below are sample output showcasing the detection capabilities of the models:
![detected emotion](https://github.com/user-attachments/assets/0604116c-c2db-4276-9e5e-38ea7401c2b5)

