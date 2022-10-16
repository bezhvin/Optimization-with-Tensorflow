# Optimization-with-Tensorflow
Using tensorflow's interfaces to do your own optimization

There are number of jupyter notebook you may open in google colab and try to learn how to use tensorflow interfaces for optimization. Tensorflow has provided a nice interface for constrained optimizations [TFCO](https://github.com/google-research/tensorflow_constrained_optimization/blob/master/README.md); while the original page also provides some nice examples, which are worth being checked out, the examples below are more general and easy to be mapped to a wide range of constrained problems.

1- [Simple optimization example](https://github.com/bezhvin/Optimization-with-Tensorflow/blob/main/SimpleExample.ipynb): It is a great start for those who want to learn from scratch. Specially if you are interested to know how to customize your optimization with some cosntraints.  
2- [Gaissian Process fit](https://github.com/bezhvin/Optimization-with-Tensorflow/blob/main/GaussianProcess.ipynb): Fitting a [Gaussian Process](https://en.wikipedia.org/wiki/Gaussian_process#:~:text=In%20probability%20theory%20and%20statistics,of%20them%20is%20normally%20distributed.) is actually fitting a multivariate gaussain distribution, with the trick that the covariance matrix is estimated by a kernel function. This is a more practical/advanced example of using tensorflow for optimization.
