# What is AutoGrad in Pytorch ?

Autograd is an automatic differentiation tool in Pytorch. It helps in performing differentiation.

## Process of Training a Neural Network:

1) Forward Pass: Compute the output of the network given an input.

2) Calculate Loss: Calculate the loss function to quantify the error.

3) Backward Pass: Compute gradients of the loss with respect to the parameters.

4) Update gradients: Adjust the parameters using an optimization algorithm (e.g gradient descent).

## Forward Pass:

1) Linear Transformation: z = wx + b (w is weight value, x is input value and b is bias value)

2) Activation Function (Sigmod in this case, relu and...etc): 
    ypred = 1/1+e^-z

3) Loss Function (Binary Corss-Entropy loss)
