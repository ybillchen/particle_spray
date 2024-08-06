# Particle spray algorithm by Chen et al. (2024)

<img src="data/movie.gif" alt="Stream generation" width="60%"/>

Author: Yingtian "Bill" Chen

We provide a notebook to generate streams using the Chen+24 ([arXiv:2408.01496](https://arxiv.org/abs/2408.01496)) model via `gala`. This implementation has not yet been merged to the `main` branch of `gala`. But you can still play with it by checking out my fork of `gala`. To do so, you need to

1. (Optional) Create a new virtual environment in case you already have your own `gala` and don't want to mess it up
```
$ conda create --name gala_chen24
$ conda activate gala_chen24
```

2. Clone my fork of `gala` and checkout the corret branch
```
$ git clone https://github.com/ybillchen/gala_chen24.git
$ cd gala_chen24
$ git checkout stream_df_chen24
```

3. Install the package
```
$ python -m pip install .
```

4. (Optional) Don't forget to switch the kernel of this notebook to the virtual environment you have just created!

Then you are done! Let's checkout what you can do in `gala_stream.ipynb`.
