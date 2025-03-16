# Modeling Market Manipulation Time-Series with a Train-on-Synthetic, Test-on-Real Approach

This repository contains various Jupyter notebooks that can be used to replicate the findings of the paper "Modeling Market Manipulation Time-Series with a Train-on-Synthetic, Test-on-Real Approach". Each method is illustrated in its own notebook.

## Notebooks

### Time Series Generation

- **GANs for Time Series**: For generating time series using Generative Adversarial Networks, see [`GAN.ipynb`](GAN.ipynb).
- **Variational Autoencoders (VAE)**: For generating time series using Variational Autoencoders, see [`VAE.ipynb`](VAE.ipynb).
- **Gaussian Sampling (GS)**: For generating time series using Gaussian Sampling, see [`GS.ipynb`](GS.ipynb).
- **Diffusion Models**: For generating time series using Diffusion models, see [`Diffusion.ipynb`](Diffusion.ipynb). ). This notebook utilizes the [denoising-diffusion-pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch) implementation.

### Evaluation Metrics

- **Tested Metrics**: For the "Tested Metrics" section, see [`Metrics.ipynb`](Metrics.ipynb).

### Classifier Accuracy Tests

- **Real vs. Generated Data**: For tests comparing classifier accuracy using real versus generated data, see [`RealVsGenerated.ipynb`](RealVsGenerated.ipynb).

## Data Requirement

To run the Jupyter notebooks, ensure you have downloaded and extracted the necessary data from [`data.zip`](data.zip). This file contains all the datasets required for the experiments detailed in the notebooks.
