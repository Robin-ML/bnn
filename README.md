# Bayesian-Neural-Network

<p>
  <a href="LICENSE"><img alt="MIT License" src="https://img.shields.io/github/license/Harry24k/bayesian-neural-network-pytorch" /></a>
  <a href="https://img.shields.io/pypi/v/torchbnn"><img alt="Pypi" src="https://img.shields.io/pypi/v/torchbnn.svg" /></a>
  <a href="https://bayesian-neural-network-pytorch.readthedocs.io/en/latest/"><img alt="Documentation Status" src="https://readthedocs.org/projects/bayesian-neural-network-pytorch/badge/?version=latest" /></a>
</p>

This is a lightweight repository of bayesian neural network for PyTorch.


### Dependencies

- torch 1.2.0
- python 3.6



### Bayesian Deep Learning

* **Bayesian Neural Network Regression** ([code](bnn_regression.ipynb)): 
Here, two-layer bayesian neural network is constructed and trained on simple custom data. It shows how bayesian-neural-network works and randomness of the model.
* **Bayesian Neural Network Classification** ([code](bnn_classification.ipynb)): 
To classify Iris data, two-layer bayesian neural network is constructed and trained on the Iris data. It shows how bayesian-neural-network works and randomness of the model.
* **Convert to Bayesian Neural Network** ([code](custom_KL_loss_with_Iris_data.ipynb)): 
To convert a basic neural network to a bayesian neural network, we show how `nonbayes_to_bayes` and `bayes_to_nonbayes` work.
* **Freeze Bayesian Neural Network** ([code](freeze_bnn.ipynb)): 
To freeze a bayesian neural network, which means force a bayesian neural network to output same result for same input, this shows the effect of `freeze` and `unfreeze`.

