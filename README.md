# Coursera-Deep-Learning-with-PyTorch-Generative-Adversarial-Network

## Configurations

device: Specify the device to run the code ('cuda' or 'cpu').

batch_size: Batch size for training.

noise_dim: Dimension of the noise vector for the Generator.

lr: Learning rate for the Adam optimizer.

beta_1, beta_2: Beta parameters for the Adam optimizer.

epochs: Number of training epochs.


## The training process consists of the following steps:

Load MNIST Dataset: Load the MNIST dataset and preprocess the images.

Create Discriminator: Define the architecture of the Discriminator neural network.

Create Generator: Define the architecture of the Generator neural network.

Initialize Weights: Initialize the weights of the networks.

Loss Function and Optimizer: Define the loss functions and initialize Adam optimizers for both networks.

Training Loop: Iterate through the dataset for a certain number of epochs, updating the weights of both networks alternately.

Generate Images: After training, generate new handwritten digit images using the trained Generator.
