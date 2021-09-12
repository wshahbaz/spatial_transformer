# Spatial Transformer Network

Spatial Transformer Network (STN) that learns and transforms input data to improve geometric invariance.

We build our STN by building a localization net (CNN) which regresses thet transformation parameters, followed by a grid generator which computes the sampling grid (Sequential NN), and finally the sampler which uses the parameters of the transformation and applies it to the image.

An example of the STN-transformed images after learning on the MNIST dataset is displayed below:




