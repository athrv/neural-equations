# Neural-Equations
A Neural Network for tracking and backtracking every neuron of an equation. Training the network using gradient descent. 

![Screenshot (11)](https://github.com/athrv/neural-equations/assets/65921445/7afcf1f2-3a36-475b-a933-ac590a6ece67)

The provided code implements a simple neural network model called Multi-Layer Perceptron (MLP). It consists of classes for `Value` (representing computation graph nodes), `Neuron` (representing a single neuron), `Layer` (representing a layer of neurons), and `MLP` (representing the entire network).

The `Value` class provides a data type of `Value` which tracks data and gradients in a computation graph and supports mathematical operations. The `Neuron` class represents a single neuron that applies weights and bias to its inputs, and applies the hyperbolic tangent activation function. The `Layer` class groups neurons together, and the `MLP` class combines multiple layers to create a complete neural network.

The code also includes a backward pass method for gradient computation and backpropagation, as well as visualization functions for the computation graph.

Overall, the code provides a framework for defining and training neural networks using automatic differentiation and gradient descent algorithm.
