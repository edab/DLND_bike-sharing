# NN for bike sharing prediction

The purpose of this project is to develop a *Neural Network (NN)* to predict bike sharing ride and is my *first project* of the [*Udacity Deep Learning Nanodegree program*](https://www.udacity.com/course/deep-learning-nanodegree--nd101).

## Quickstart

This project is based on [Pytorch](https://pytorch.org/) and [Jupyter notebook](https://jupyter.org/). All the installation process are handled by [Anaconda](https://www.anaconda.com/), one of the the most popular ***Data Science platform***, so is quite straightforward.

Download and install the ***Anaconda platform*** for the OS and architecture in use:

    $ wget https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh
    $ ./Anaconda3-2019.03-Linux-x86_64.sh

Create an ***Anaconda environment*** for the project based on Python 3.6:

    $ conda install python=3.6.8
    $ conda create -n dog-breed python=3.6
    $ conda activate dog-breed

Install all the ***required dependencies*** always using Anaconda:

    $ conda install -c conda-forge matplotlib
    $ conda install numpy jupyter notebook
    $ conda install pytorch-cpu torchvision-cpu -c pytorch


## Dataset

The [dataset](Bike-Sharing-Dataset/) is based on the **Bike Sharing Dataset** by Hadi Fanaee-T of the Laboratory of Artificial Intelligence and Decision Support (LIAAD), University of Porto.

## Goal

The aim of the project is to design the Forward and Backward pass of the Neural Network, and tune the Hyper-parameters to achieve a training loss below ***0.09*** and a validation loss below ***0.18***.

## Results

The project submitted shown a training loss of ***0.063*** and a validation loss of ***0.139***, and **meet** all the requirements:

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
