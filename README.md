## Overview
## Setup
```bash
conda create -n python-dl-tutorial python=3.11 -y
conda activate python-dl-tutorial
pip install tensorflow numpy matplotlib
conda deactivate
```
## Topics
- input, hidden, and output layers
  - Input layer: the first layer that receives raw data and feeds it into the network
  - Hidden layer: intermediate layers between input and output that perform computations and feature extraction
  - Output layer: the final layer that produces the network's predictions or classifications
- Weight, value, bias
  - Weight: parameters that determine the strength and direction of connections between neurons
  - Bias: additional parameters that shift the activation function to allow for more flexible learning
  - Value: the computed output of a neuron after applying weights, biases, and activation functions
- Activation functions
  - ReLU: Rectified Linear Unit that outputs the input if positive, zero otherwise - introduces non-linearity
  - Sigmoid: S-shaped function that squashes values between 0 and 1, useful for binary classification
  - Tanh: Hyperbolic tangent function that outputs values between -1 and 1, centered at zero
- Loss functions
  - MSE: Mean Squared Error that measures the average of squared differences between predicted and actual values
  - Cross-entropy: measures the difference between probability distributions, ideal for classification tasks
  - Custom loss: user-defined loss functions tailored to specific problem domains or requirements
- Epochs
  - Epoch: one complete pass through the entire training dataset during model training
  - Multiple epochs: repeated passes that allow the model to learn better patterns in the data
  - Early stopping: technique to halt training when performance on validation data starts degrading