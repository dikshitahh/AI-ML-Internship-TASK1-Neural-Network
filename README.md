# AI-ML-Internship-TASK1-Neural-Network

# Basic Neural Network using TensorFlow

## Objective

The objective of this task is to understand the fundamentals of neural networks and deep learning by implementing a basic neural network model using TensorFlow/Keras. The model is trained to classify handwritten digits from the MNIST dataset while learning about neural network architecture, activation functions, and backpropagation.

## Tools and Libraries Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

MNIST Handwritten Digits Dataset

- 70,000 grayscale handwritten digit images
- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- 10 output classes (digits 0–9)

## Steps Performed

1. Imported the required libraries.
2. Loaded the MNIST dataset.
3. Explored the dataset by checking its shape and visualizing sample images.
4. Normalized the pixel values.
5. Built a neural network using TensorFlow/Keras.
6. Compiled the model using the Adam optimizer and Sparse Categorical Crossentropy loss function.
7. Trained the model for multiple epochs.
8. Evaluated the model on the test dataset.
9. Generated predictions.
10. Visualized training accuracy, validation accuracy, training loss, validation loss, and the confusion matrix.
11. Generated the classification report.
12. Saved the trained neural network model.

## Neural Network Architecture
----------------------------------------------------
| Layer              | Configuration               |
|--------------------|-----------------------------|
| Flatten            | Input Shape (28 × 28)       |
| Hidden Layer 1     | Dense (128 neurons, ReLU)   |
| Hidden Layer 2     | Dense (64 neurons, ReLU)    |
| Output Layer       | Dense (10 neurons, Softmax) |
----------------------------------------------------

## Results

The neural network successfully learned to classify handwritten digits from the MNIST dataset with high accuracy.

Model Outputs:

- Training Accuracy Graph
- Training Loss Graph
- Confusion Matrix
- Classification Report
- Saved Trained Model

## Learning Outcomes

Through this task, I learned:

- Fundamentals of Deep Learning
- Neural Network Architecture
- Artificial Neurons
- Hidden and Output Layers
- Activation Functions (ReLU and Softmax)
- Loss Functions
- Optimizers (Adam)
- Backpropagation
- Image Classification using TensorFlow/Keras
- Model Evaluation using Accuracy, Confusion Matrix, and Classification Report

## Conclusion
This project demonstrates the implementation of a basic neural network for handwritten digit classification using TensorFlow. The model was successfully trained, evaluated, and achieved high classification accuracy, providing practical experience in building and evaluating deep learning models.
