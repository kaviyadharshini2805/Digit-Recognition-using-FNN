# Handwritten Digit Recognition using Feedforward Neural Network

## Overview

This project implements handwritten digit classification on the MNIST dataset using a Feedforward Neural Network (FNN) built with TensorFlow and Keras. It demonstrates the complete workflow, including data preprocessing, model creation, training, and evaluation.

## Dataset

The model is trained on the MNIST dataset, which contains grayscale images of handwritten digits from 0 to 9.

* Training images: 60,000
* Test images: 10,000
* Image size: 28 × 28 pixels
* Number of classes: 10

## Model Architecture

* Flatten layer to convert 28 × 28 images into a 784-dimensional vector
* Dense hidden layer with 100 neurons using the Tanh activation function
* Dense output layer with 10 neurons for digit classification

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook

## Data Preprocessing

* Loaded the MNIST dataset from Keras
* Normalized pixel values to the range 0–1
* Flattened input images before passing them to the network

## Results

The model is trained for 5 epochs and achieves approximately **97% training accuracy** after normalization and the addition of a hidden layer.

## Repository Structure

```text
.
├── handwritten_digit_recognition.ipynb
└── README.md
```

## Run the Project

1. Clone the repository.

```bash
git clone https://github.com/kaviyadharshini2805/Digit-Recognition-using-FNN.git
```

2. Install the required packages.

```bash
pip install tensorflow numpy matplotlib
```

3. Open the notebook.

```bash
jupyter notebook handwritten_digit_recognition.ipynb
```

## Future Improvements

* Compare different activation functions
* Evaluate different optimizers
* Add confusion matrix and classification report
* Implement a Convolutional Neural Network (CNN) for comparison

## License

This project is intended for learning and educational purposes.
