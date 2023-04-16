# Autoencoders on MNIST dataset

This repository contains two Jupyter notebooks (`denoiser.ipynb` and `VAE.ipynb`) that implement denoising autoencoder and variational autoencoder on the MNIST dataset.

Denoising Autoencoder
The denoising autoencoder notebook trains on corrupted images of MNIST dataset and reconstruct images with denoiser, and evaluates it using mean residual and first five principal coordinates.

To run the notebook, ensure that you have installed the following dependencies:

- Python 3.x
- Pytorch
- NumPy
- Matplotlib
- Sklearn
Then, open the `denoiser.ipynb` file in Jupyter and run the cells in order.

Variational Autoencoder
The variational autoencoder notebook trains a variational autoencoder on the MNIST dataset and evaluates it by showing autoencoded interpolations between the same digit pairs and different digit pairs.

To run the notebook, ensure that you have installed the following dependencies:

- Python 3.x
- Pytorch
- NumPy
- Matplotlib
Then, open the variational_autoencoder.ipynb file in Jupyter and run the cells in order.

Note: Both notebooks use the MNIST dataset, which is included in Pytorch. If you have previously downloaded the dataset, please update the path accordingly.




Regenerate response
