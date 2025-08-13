# neural-network-classifier
Feed forward neural network with back propogation using numpy 


This file consist of basic Artificial neural network (Feed forward neural network). whose work is to to identify a synthetic image of Letter A, B and C. 
This neural network is consist of 1 hidden layer with input and output layer.

the input is consist of thre 2D arrays of shape (5,6) made up of 1s and 0s.

a = [
    [0, 0, 1, 1, 0, 0],
    [0, 1, 0, 0, 1, 0],
    [1, 1, 1, 1, 1, 1],
    [1, 0, 0, 0, 0, 1],
    [1, 0, 0, 0, 0, 1]
]

b = [
    [0, 1, 1, 1, 1, 0],
    [0, 1, 0, 0, 1, 0],
    [0, 1, 1, 1, 1, 0],
    [0, 1, 0, 0, 1, 0],
    [0, 1, 1, 1, 1, 0]
]

c = [
    [0, 1, 1, 1, 1, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 1, 1, 1, 0]
]


The activation function used in this neural network is a sigmoid function 

S(x) = 1/(1+ e^(-x))

Using mean square error to calculate the losses and back track it into adjusting the weights.

In the function f_forward :
inputs are x (array) , w1 (weight for the input), w2 (weight of the hidden layer)

In the function back_prop(back propogation):
inputs are {inputs of f_forward} , y (target array) and alpha (learning rate)

In the function of train:
new input is epoch (iterations).


