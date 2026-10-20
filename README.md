# TSTR for Financial Fraud: Learning to Detect Manipulation Without Real Data

This repository contains various Jupyter notebooks that can be used to replicate the findings of the paper "TSTR for Financial Fraud: Learning to Detect Manipulation Without Real Data". Each method is illustrated in its own notebook.

Ahmed Mahrous and Roberto Di Pietro. *Proceedings of the 6th ACM International Conference on AI in Finance*, pp. 71–79, 2025.

[Published paper](https://doi.org/10.1145/3768292.3770393) · [Paper page](https://amahrous.com/papers/tstr-financial-fraud/)

## Notebooks

### Time Series Generation

- **GANs for Time Series**: For generating time series using Generative Adversarial Networks, see [`GAN.ipynb`](GAN.ipynb).
- **Variational Autoencoders (VAE)**: For generating time series using Variational Autoencoders, see [`VAE.ipynb`](VAE.ipynb).
- **Gaussian Sampling (GS)**: For generating time series using Gaussian Sampling, see [`GS.ipynb`](GS.ipynb).
- **Diffusion Models**: For generating time series using Diffusion models, see [`Diffusion.ipynb`](Diffusion.ipynb). This notebook utilizes the [denoising-diffusion-pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch) implementation.

### Evaluation Metrics

- **Tested Metrics**: For the "Tested Metrics" section, see [`Metrics.ipynb`](Metrics.ipynb).

### Classifier Accuracy Tests

- **Real vs. Generated Data**: For tests comparing classifier accuracy using real versus generated data, see [`RealVsGenerated.ipynb`](RealVsGenerated.ipynb).

## Data Requirement

To run the Jupyter notebooks, ensure you have downloaded and extracted the necessary data from [`data.zip`](data.zip). This file contains all the datasets required for the experiments detailed in the notebooks.

## Citation

If you use this repository, please cite:

```bibtex
@inproceedings{mahrous2025tstr,
  title={TSTR for Financial Fraud: Learning to Detect Manipulation Without Real Data},
  author={Mahrous, Ahmed and Di Pietro, Roberto},
  booktitle={Proceedings of the 6th ACM International Conference on AI in Finance},
  year={2025},
  pages={71--79},
  doi={10.1145/3768292.3770393},
  url={https://doi.org/10.1145/3768292.3770393}
}
```
