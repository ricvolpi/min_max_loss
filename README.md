# Code for the paper [Minimizing the Maximal Loss: How and Why](https://arxiv.org/pdf/1602.01690.pdf)

Unofficial implementation of the work by Shalev-Schwartz and Wexler (ICML 2016). Work in progress.

## Getting started

The code allows to train a ConvNet on MNIST using the sampling procedure described in the paper. 

### Prerequisites

Python 2.7 (should work on Python 3, too), Numpy, Tensorflow 1.3 

### Files

Tree.py: class to build and sample from the full binary tree

Model.py: class to build and train a ConvNet.

FOL.py: class to run the algorithm on MNIST. 
