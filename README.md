# Hand Written Digits Recognition

Created 2 simple models to predict handwritten digits from MNIST dataset.
One model has only one layer that has 784 neurons since our flattened array's shape is 784. The activation function used in this layer is sigmoid. The output layer has 10 neurons since we are predicting 0-9 digits. The neuron with the highest value would be the predicted label.
The second model has 2 layers. First layer is using the relu activation function and its output is 100 and the second layer is using sigmoid activation function and its output is again 10.