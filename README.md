# Self-Normalizing Networks
Tutorials and implementations for "Self-normalizing networks"(SNNs) as suggested by Klambauer et al. ([arXiv pre-print](https://arxiv.org/pdf/1706.02515.pdf)). 

## Versions
- Python 3.5 and Tensorflow 1.1

## Tutorials
- Multilayer Perceptron ([notebook](https://github.com/bioinf-jku/SNNs/blob/master/SelfNormalizingNetworks_MLP_MNIST.ipynb))
- Convolutional Neural Network on MNIST ([notebook](https://github.com/bioinf-jku/SNNs/blob/master/SelfNormalizingNetworks_CNN_MNIST.ipynb))
- Convolutional Neural Network on CIFAR10 ([notebook](https://github.com/bioinf-jku/SNNs/blob/master/SelfNormalizingNetworks_CNN_CIFAR10.ipynb))

## Design novel SELU functions
- How to obtain the SELU parameters alpha and lambda for arbitrary fixed points ([notebook](https://github.com/bioinf-jku/SNNs/blob/master/getSELUparameters.ipynb))

## Basic python functions to implement SNNs
are provided as code chunks here: [selu.py](https://github.com/bioinf-jku/SNNs/blob/master/selu.py)

## Notebooks and code to produce Figure 1
are provided here: [Figure1](https://github.com/bioinf-jku/SNNs/blob/master/figure1/)

## Calculations and numeric checks of the theorems (Mathematica)
are provided as mathematica notebooks here:

- [Mathematica notebook](https://github.com/bioinf-jku/SNNs/blob/master/Calculations/SELU_calculations.nb)
- [Mathematica PDF](https://github.com/bioinf-jku/SNNs/blob/master/Calculations/SELU_calculations.pdf)

## UCI, Tox21 and HTRU2 data sets

- [UCI](http://persoal.citius.usc.es/manuel.fernandez.delgado/papers/jmlr/data.tar.gz)
- [Tox21](http://bioinf.jku.at/research/DeepTox/tox21.zip)
- [HTRU2](https://archive.ics.uci.edu/ml/machine-learning-databases/00372/HTRU2.zip)