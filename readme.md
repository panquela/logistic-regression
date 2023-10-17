![version](https://img.shields.io/badge/Last%20Stable%20Release-1.0.0-green?logo=serverfault)

# Using Machine Learning for a Linear Regression Model

Welcome to the Linear Regression Model. This code snippet trains a Pytorch model to fit a dataset that matches a linear regression.

Walking through the code, you'll be able to find the four main building blocks of every single Neural Network model:

 * <br>Forward pass</br>: in this step we plug in a batch of our training data and get the output. Then we compare the result of our model and the actual data using a loss function.
 * <br>Backward pass</br>: this step deals with the math necessary to make the optimization work.
 * <br>Optimization</br>: here we modify the weights and bias of our model in order to approach our results to the actual data and, therefore, minimize the loss
 * <br>Repetition</br>: we repeat the algorithm as many times as the number of epochs defines.