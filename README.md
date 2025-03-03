# Handwritten Digit Recognition with a Neural Network (No TensorFlow/PyTorch)

## Overview
This repository contains a Jupyter Notebook (`nn_hw_numpy.ipynb`) that implements a neural network from scratch using only NumPy. The model is trained on the [MNIST dataset](http://yann.lecun.com/exdb/mnist/) to recognize handwritten digits (0-9).

## Features
- Implements a fully connected neural network with forward and backward propagation.
- Uses only NumPy—no TensorFlow, PyTorch, or other deep learning frameworks.
- Trains on the MNIST dataset, which consists of 28x28 grayscale images.
- Includes functions for data preprocessing, network initialization, training, and evaluation.

## Installation
To set up the required dependencies, install the packages listed in `requirements.txt`.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/neural_network_numpy.git
   cd neural_network_numpy
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook nn_hw_numpy.ipynb
   ```

3. Run the notebook cells to train the neural network on the MNIST dataset.

## Dataset
The MNIST dataset can be downloaded from [this link](http://yann.lecun.com/exdb/mnist/). The notebook includes code to automatically fetch and preprocess the dataset.

## Results
After training, the neural network achieves 93.95% accuracy on handwritten digit recognition(check the `save_1.json` and load into the NN, code included). Further improvements can be made by tweaking the architecture and hyperparameters.

## Contributing
Feel free to open issues or submit pull requests if you want to enhance the implementation.

## License
This project is open-source and available under the MIT License.
