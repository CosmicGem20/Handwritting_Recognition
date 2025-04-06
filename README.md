#✍️ Handwritten Digit Recognition using CNN
This project demonstrates a deep learning model built with Convolutional Neural Networks (CNN) using TensorFlow and Keras to recognize handwritten digits from the famous MNIST dataset.

The model takes grayscale images of handwritten digits (0–9) as input and predicts the correct digit class. The MNIST dataset contains 70,000 labeled images (28x28 pixels), making it an ideal beginner dataset for computer vision and neural network projects.

#🔍 Problem Statement
The goal is to accurately classify handwritten digit images using a CNN model. The network learns features like edges, curves, and shapes to distinguish between digits effectively.

#🚀 Features
Uses CNN for feature extraction and classification

Trained on the MNIST dataset

Achieves high accuracy on the test set

Visualizes predictions on sample images

#🧠 Algorithms & Technologies
Convolutional Neural Network (CNN) for image classification

TensorFlow and Keras for building and training the model

Matplotlib for visualization

#🛠️ How it Works
Data Preprocessing:
Normalize pixel values and reshape images to fit CNN input requirements.

Model Architecture:

2 Convolutional layers with ReLU activation and MaxPooling

Flatten layer

Dense (fully connected) layer

Output layer with Softmax activation for multi-class classification

##Training:
Trained for 5 epochs using the Adam optimizer and categorical cross-entropy loss.

##Evaluation:
Model is evaluated on the test set for accuracy.
