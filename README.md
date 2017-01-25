# unsupervised-preprocessing

Unsupervised preprocessing notebooks from Task 1.1.

## Task description

Transformation of raw tactile data from sensor space into a latent space. This latent space represents the data in a way that is better suited for control and other supervised prediction tasks.

More information can be found in the corresponding paper: [Unsupervised preprocessing for Tactile Data](https://arxiv.org/abs/1606.07312).

## Notebooks

There is an ipython notebook for each sensor and dataset combination:

- VAE for tactile BioTac Curvature.ipynb
- VAE for tactile BioTac Shore.ipynb
- VAE for tactile BioTac Surface.ipynb
- VAE for tactile iCub Curvature.ipynb
- VAE for tactile iCub Shore.ipynb
- VAE for tactile iCub Surface.ipynb

Every notebooks initializes and trains a Variational Autoencoder on the specified dataset and also creates some visualisations.

## Prerequisites

- [breze](http://www.github.com/breze-no-salt/breze)
- [climin](https://github.com/BRML/climin)

## How to run 

In the notebooks folder run:

```
ipython notebook
```

Then start each notebook with the web interface.
