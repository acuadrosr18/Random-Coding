# Random-Coding

## Building a Neural Network for Fashion MNIST Classification

This project demonstrates how to build a simple neural network model for classifying images from the Fashion MNIST dataset using TensorFlow and Keras.

### Overview

This notebook covers the following steps:

1. **Dataset Loading**: 
   - Loads the Fashion MNIST dataset, which consists of 70,000 grayscale images of 10 different fashion categories.
   
2. **Data Visualization**: 
   - Visualizes a sample of the dataset to better understand the structure of the input data.
   
3. **Model Creation**: 
   - Constructs a simple neural network model using Keras' Sequential API.
   - The model includes:
     - A Flatten layer to convert each image from a 28x28 matrix into a 1D vector.
     - A Dense layer that serves as the output layer to classify the images into 10 categories.
   
4. **Model Compilation**: 
   - Uses the `Adam` optimizer and the `Sparse Categorical Crossentropy` loss function to prepare the model for training.
   
5. **Model Training**: 
   - Trains the model on the training set, using 5 epochs, while validating the performance on the validation set.
   
6. **Prediction and Evaluation**: 
   - Makes predictions on unseen images.
   - The results are visualized by plotting the predicted probabilities for each class.
   
7. **Visualization**: 
   - Displays the input images and the corresponding model predictions using `matplotlib`.

### Dependencies

- Python 3.x
- TensorFlow 2.x
- matplotlib

You can install the required libraries using the following:

```bash
pip install tensorflow matplotlib

