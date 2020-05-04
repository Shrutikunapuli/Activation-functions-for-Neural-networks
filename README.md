# Activation-functions-for-Neural-networks

In simple words, the activation function is an equation that is used to convert an input of a node in a Neural network/Layer to an output. It is a logic “gate” in between the input feeding the current neuron and its output going to the next layer(if stacked).

The main objective of the activation function is to introduce non-linearilty to neuron and determine whether to activate a neuron in a layer or not. Such that, during model building, only the activated neurons are considered.


## Basic features of any activation function are:
1) It must be differential- In the process of backpropgation.

2) Ideally Non-linear - They allow the model to create complex mappings between the network’s inputs and outputs, which are essential for learning and modeling complex and multidimensional data.

There are several activation functions, can be compared by computational efficiency because they are calculated across thousands and millions of data or by taking gradient.


## Widely used activation functions are as follows:
1) Sigmoid

2) Tanh(Hyperbolic tangent)

3) ReLU(Rectified Linear Unit) and its varients

4) Softmax

5) Swish
