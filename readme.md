# Hand Digit Recognition using CNN

This repository contains a Convolutional Neural Network (CNN) implementation for handwritten digit recognition using TensorFlow and Keras.

## Project Overview

This project implements a CNN model to recognize handwritten digits with high accuracy. Two different approaches are included:

1. **MNIST.ipynb**: Uses the standard MNIST dataset (60,000 training samples, 10,000 testing samples)
2. **47_99accuracy_pro_players.ipynb**: Uses custom hand-drawn digits stored in the `new_digits_2` folder

## CNN Architecture

The model uses a multi-layer CNN architecture:

```
Input → Conv2D → ReLU → MaxPooling → Conv2D → ReLU → MaxPooling → Conv2D → ReLU → Flatten → Dense → ReLU → Dense → Softmax
```

![CNN Architecture](https://miro.medium.com/max/2000/1*vkQ0hXDaQv57sALXAJquxA.jpeg)

## Results

- The model trained on the MNIST dataset achieves high accuracy on standard test data
- The model trained on custom hand-drawn digits achieves 99.47% accuracy, demonstrating excellent generalization capabilities

## Files Description

- **MNIST.ipynb**: Jupyter notebook implementing CNN with standard MNIST dataset
- **47_99accuracy_pro_players.ipynb**: Jupyter notebook implementing CNN with custom hand-drawn digits
- **new_digits_2/**: Folder containing custom hand-drawn digit images
- **Hand_Digit.pdf**: Detailed documentation with project insights, methodology, and results analysis

## Requirements

- TensorFlow 2.x
- NumPy
- Matplotlib
- scikit-learn

## How to Run

1. Clone this repository
2. Install the required dependencies: `pip install tensorflow numpy matplotlib opencv-python scikit-learn seaborn`
3. Run the Jupyter notebooks

## Further Information

For more detailed insights into the project methodology, implementation details, and results analysis, please refer to the `Hand_Digit.pdf` document included in this repository.
