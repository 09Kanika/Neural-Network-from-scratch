# Neural Network Implementation using only Numpy
### Problem Statement: 
* This repository contains the implementation of Neural Network from scratch using numpy.
### General Architecture:
- __Input Layer__:
    The input layer will have 2400 data points. 
- __Hidden Layer__:
    Typically, we start with a few hidden layer with ReLU activation function.
- __Output Layer__:
    This layer will have 3 units with Softmax activation function to output class probabilities.
### Objective:
* Create a dataset using `nnfs` library.
* Implement neural network architecture on the created dataset.
* Train the neural network using forward propagation.
* Evaluate the accuracy of the neural network.
### Dataset:
To create a dataset, we will use `vertical_data` method from `nnfs.datasets`, that generates a dataset. 
The function takes two arguments:
* `samples` : 800 - This specifies that the function should generate 800 samples in the dataset.
* `classes` : 3 - This specifies that the dataset should have 3 distinct classes or categories for the target labels `y`.

### Aproach:
* Define neural network architecture.
* Implement forward propagation, activation functions (ReLU and Softmax), loss function (Cross-Entropy)
* Generate sample dataset  from `nnfs.datasets`.
* Evaluate the accuracy of the neural network.

### Tools:
* NumPy:For numerical computing and linear algebra operations.


## Usage:

1. Clone the repository:
`git clone https://github.com/09Kanika/Neural-Network-from-scratch.git`

2. Install dependencies:
`pip install -r requirements.txt`

3. Run the Jupyter notebook `neural_network_from_scratch.ipynb` to train and evaluate the neural network.

### References:
- NumPy documentation: https://numpy.org/doc/stable/
- Pandas documentation: https://pandas.pydata.org/pandas-docs/stable/
- Prerequisite: https://www.youtube.com/watch?v=Wo5dMEP_BbI&list=PLQVvvaa0QuDcjD5BAw2DxE6OF2tius3V3
