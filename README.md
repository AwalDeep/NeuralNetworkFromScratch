# NeuralNetworkFromScratch
My own implementation for training my own neural network.

The goal is to label images of 10 handwritten digits of “zero”, “one”,..., 
“nine”. The images are 28 by 28 in size (MNIST dataset), which we will be represented as a vector x of 
dimension 784 by listing all the pixel values in raster scan order. The labels t are 0,1,2,...,9 corresponding 
to 10 classes as written in the image. 
This is generalised code for any number of hidden layers.
I have used softmax activation for output layer and we can apply any activation at hidden layers.
I have also implemented stochastic gradient descent with momentum.
