# mldt

# MLDT: Multi-Layer Diffusion Theory

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

**MLDT** is a fast, open-source Python package for calculating steady-state diffuse reflectance spectra ($R_d$) in multi-layered turbid media using the $P_1$ diffusion approximation. 

By formulating multi-layer boundary conditions into an efficient, banded matrix structure, MLDT achieves sub-millisecond forward solver execution speeds—making it ideal for real-time iterative inverse extraction of optical properties in tissue spectroscopy and biomedical imaging.

The complete solver and demonstration workflow are provided as a single Jupyter Notebook (`.ipynb`). The file can easily be uploaded to Google Drive and run directly in Google Colab, enabling anyone to execute forward modeling and inverse routines without installing a local environment.

## Citation
If you use MLDT in your research, please cite our manuscript published in the Journal of Biomedical Optics (JBO):

Livecchi, T. T., Jacques, S. L., & Pierce, M. C. (2026). MLDT: An open-source
multilayer diffusion theory Python implementation. Journal of Biomedical Optics.
