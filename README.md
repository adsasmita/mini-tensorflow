# mini-tensorflow
A simple Neural Network architecture that mimics [TensorFlow](https://www.tensorflow.org/) built from scratch using Numpy.

##How to Use

The code is presented in a [Jupyter Notebook](https://github.com/jupyter/notebook) / iPython notebook.

Open or download [`neural-network.ipynb`](https://github.com/adsasmita/mini-tensorflow/blob/master/neural-network.ipynb) and run the cells in a Python 3 environment.

##Overview

The architecture invokes **Class** `Node`, which consists of **Sub-Classes** `Input`, `Linear`, `Sigmoid` and `MSE` (mean-squared error).

Both forward and backward passes are implemented in each node.

To reduce computations and memory consumption, the backpropagated errors are minimized using [Stochastic Gradient Descent](http://sebastianruder.com/optimizing-gradient-descent/index.html#stochasticgradientdescent) method.

##Testing

This project uses the [Boston Housing dataset](https://archive.ics.uci.edu/ml/datasets/Housing) to test the effectiveness of the NN architecture. ``neural-network.ipynb`` will try to predict Boston housing prices by minimizing the cost / error function of the model.

After training (here the training epochs is set to ``1000``)the network will be able to predict prices of Boston housing!

##Dependencies

* [Numpy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [matplotlib](http://matplotlib.org/)
* [SciKit-Learn](http://scikit-learn.org/)


