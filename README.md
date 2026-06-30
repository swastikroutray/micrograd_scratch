PROJECT OVERVIEW - 

~This project is a from-scratch implementation of a simple neural network inspired by Andrej Karpathy's **Micrograd**. 
The goal of the project is to demonstrate the fundamental concepts behind neural networks and automatic differentiation 
without relying on high-level deep learning frameworks.

~The project implements the core building blocks of a neural network, including neurons, layers, and a multi-layer perceptron (MLP). 
It constructs a computation graph during the forward pass and performs automatic differentiation using backpropagation to compute 
gradients for every trainable parameter.

~The network is trained using gradient descent, where the loss between the predicted and target outputs is minimized by iteratively updating 
the weights and biases. The project also includes an implementation of common mathematical operations such as addition, multiplication, 
exponentiation, and the `tanh` activation function, each with its corresponding backward pass for gradient computation.

~To validate the implementation, the project compares its manually implemented automatic differentiation engine with PyTorch's `autograd`, 
demonstrating that both produce the same gradients and follow the same underlying principles.

~Overall, this project provides a clear and intuitive implementation of the core mechanics behind modern deep learning frameworks, 
showing how forward propagation, computational graphs, backpropagation, gradient descent, and automatic differentiation work together 
to train a neural network.
