# Autograd Engine

A simple implementation of a scalar-based automatic differentiation engine built from scratch in Python.
The `Value` class builds a computational graph and automatically calculates gradients using reverse-mode automatic differentiation.

## Features

- Scalar automatic differentiation
- Computational graph construction
- Backpropagation
- Basic mathematical operations: Addition, Subtraction etc. as well as Tanh, Sigmoid, ReLU
- Numerical gradient checking
- Computational graph visualization
- Simple neural network implementation
- Multi-layer perceptron (MLP) training from scratch

## Neural Network

The notebook builds and trains a small MLP with the architecture:

```text
3 inputs → 4 neurons → 4 neurons → 1 output
