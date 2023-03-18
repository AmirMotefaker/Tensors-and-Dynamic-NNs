# Tensors-and-Dynamic-NNs
Tensors and Dynamic neural networks in Python with and without GPU acceleration

# NOTE

At its core, [PyTorch](https://pytorch.org/) provides two main features:

- An n-dimensional Tensor, similar to [NumPy](https://numpy.org/) but can run on GPUs

- Automatic differentiation for building and training neural networks

We will use a problem of fitting y=sin(x) with a third-order polynomial as our running example. The network will have four parameters and will be trained with gradient descent to fit random data by minimizing the [Euclidean distance](https://www.cuemath.com/euclidean-distance-formula/) between the network output and the true output.
