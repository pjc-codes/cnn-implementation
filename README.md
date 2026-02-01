# Convolutional Neural Networks Implementation

This repository contains a Jupyter notebook implementing a convolutional neural network (CNN) for handwritten digit classification on the MNIST dataset using TensorFlow / PyTorch.

The notebook demonstrates:

- A CNN architecture with:

- Two convolutional blocks (Conv2D + ReLU + MaxPooling)

- Fully connected layers with dropout

- Implementation using the Keras Functional API, subclassing Keras `Model` class, and Pytorch.

- Proper handling of logits vs softmax in the output layer

## CNN Model Architecture

- Input: 28 × 28 × 1 grayscale images

- Conv block 1: 3×3 conv (32 filters) + max pooling

- Conv block 2: 3×3 conv (64 filters) + max pooling

- Dense layer: 128 units + ReLU

- Dropout: 0.5

- Output: 10-class classification (logits)

## Requirments

- `pyproject.toml` and `uv.lock` can be used to recreate the working environment.
