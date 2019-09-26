# Multi-Layer-Perceptron
Self-Coded Multi-Layer Perceptron without use of available neural network/connectionist/machine learning/... libraries.

This software is completes the following:
- [x] Create a new MLP with any given number of inputs, any number of outputs (can be sigmoidal or linear), and any number of hidden units (sigmoidal/tanh) in a single layer.
- [x] Initialise the weights of the MLP to small random values
- [x] Predict the outputs corresponding to an input vector
- [x] Implement learning by backpropagation


Testing:
1. Train an MLP with 2 inputs, two hidden units and one output on the following examples (XOR function):
   ((0, 0), 0)
   ((0, 1), 1)
   ((1, 0), 1)
   ((1, 1), 0)
2. At the end of training, check if the MLP predicts correctly all the examples.


In case GitHub can't render the notebook ("Sorry, something went wrong. Reload?"):
https://nbviewer.jupyter.org/github/michjord0001/Multi-Layer-Perceptron/blob/master/MultiLayerPerceptron.ipynb
