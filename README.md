# FFNN
Feedforward Neural Network with 2 hidden layers, implemented in MATLAB with no library or toolbox dependencies. 784x784x784(x10)x1 network architecture with 2000 iterations of a BFGS variant achieved 98.34% test accuracy.
# How to use
Run the init.mlx file in MATLAB
# Parameters
Set the maximum iterations to n with options = optimset('MaxIter', n);, lambda with lambda and the number of units in the hidden layers with hidden_layer_size.
