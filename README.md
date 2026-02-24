# Particle spray algorithm by Chen et al. (2025)

[![version](https://img.shields.io/badge/version-v0.1.0-blue)](https://github.com/ybillchen/particle_spray)
[![license](https://img.shields.io/github/license/ybillchen/particle_spray)](LICENSE)
[![ADS](https://img.shields.io/badge/ADS-2025ApJS..276...32C-blue)](https://ui.adsabs.harvard.edu/abs/2025ApJS..276...32C/abstract)
[![arXiv](https://img.shields.io/badge/arXiv-2408.01496-green)](https://arxiv.org/abs/2408.01496)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13923250.svg)](https://doi.org/10.5281/zenodo.13923250)

<img src="data/movie.gif" alt="Stream generation" width="75%"/>

Animation: positions and velocity vectors of escaped stream particles. Download the animation at [`data/movie.gif`](data/movie.gif) or [`data/movie.mp4`](data/movie.mp4).

## Notebooks

We provide notebooks to generate mock streams using the Chen+25 model via `agama`, `gala`, `galax`, `galpy`, and `StreaMAX`. Checkout these notebooks and follow the instructions therein!

- `agama`: [`agama_stream.ipynb`](agama_stream.ipynb)
- `gala`: [`gala_stream.ipynb`](gala_stream.ipynb)
- `galax`: [`galax_stream.ipynb`](galax_stream.ipynb)
- `galpy`: [`galpy_stream.ipynb`](galpy_stream.ipynb)
- `StreaMAX`: [`David-Chemaly/StreaMAX/quick_start.ipynb`](https://github.com/David-Chemaly/StreaMAX/blob/main/quick_start.ipynb)

## Citation

We recommend citing this algorithm as Chen+25, although it was referred to as Chen+24 since the method paper was originally submitted to arXiv in 2024.

If you use this algorithm for a publication, we kindly request you to cite the following original paper:

- Y. Chen, M. Valluri, O. Y. Gnedin, & N. Ash (2025) *Improved particle spray algorithm for modeling globular cluster streams*, [ApJS](https://doi.org/10.3847/1538-4365/ad9904) **276**, 32. [arXiv:2408.01496](https://arxiv.org/abs/2408.01496), [ADS link](https://ui.adsabs.harvard.edu/abs/2025ApJS..276...32C/abstract)
