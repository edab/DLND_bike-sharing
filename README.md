# NN for bike sharing prediction

This project will develop a *Neural Network* to predict bike sharing ride.

This is my first project for the *Udacity Deep Learning Nanodegree*, an is based on Torch and jupyter notebook.

## Dataset

The dataset is based on the **Bike Sharing Dataset** by Hadi Fanaee-T of the Laboratory of Artificial Intelligence and Decision Support (LIAAD), University of Porto.

## Goal

The aim of the project is to design the Forward and Backward pass of the Neural Network, and tune the Hiperparameters to achieve a training loss below ***0.09*** and a validation loss below ***0.18***.

## Results

The project submitted has a training loss of ***0.061*** and a validation loss of ***0.135***, and **meet** all the requirements:

  - `Code Functionality`
    - All the code in the notebook runs in ***Python 3*** without failing
    - All ***unit tests*** pass.
    - The ***sigmoid activation function*** is implemented correctly.
  - `Forward Pass`
    - The ***forward pass*** is correctly implemented for the network's training.
    - The ***run method*** correctly produces the desired regression output for the neural network.
  - `Backward Pass`
    - The network correctly implements the ***backward pass*** for each batch, correctly updating the weight change.
    - Updates to both the ***input-to-hidden*** and ***hidden-to-output*** weights are implemented correctly.
  - `Hyperparameters`:
    - The ***number of epochs*** is chosen such the network is trained well enough to accurately make predictions but is not _overfitting_ to the training data.
    - The ***number of hidden units*** is chosen such that the network is able to accurately predict the number of bike riders, is able to _generalize_, and is not _overfitting_.
    - The ***learning rate*** is chosen such that the network successfully converges, but is still time efficient.
    - The ***number of output nodes*** is properly selected to solve the desired problem.
    - The ***training loss*** is below _0.09_ and the validation loss is below _0.18_.
