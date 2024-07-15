# particle_spray_chen24

Author: Yingtian "Bill" Chen

I provide a notebook to generate streams using the Chen+24 model via `gala`.

Currently, only the "fix parameter" version is implemented in `gala`; and this implementation has not yet been merged to the `main` branch of `gala`. But you can still play with it by checking out my fork of `gala`. To do so, you need to

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

4. (Optional) Create a `ipython` kernel for the virtual environment you have just created
```
$ pip install ipykernel
$ python -m ipykernel install --user --name gala_chen24 --display-name "Python (gala_chen24)"
```
    And don't forget to switch the kernel of this notebook!

Then you are done! Let's checkout what you can do in `gala_stream.ipynb`.