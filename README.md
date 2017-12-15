# Introduction

The purpose of this repo is to provide a unified software environment for the participants of the "User identification based on keystroke dynamics" workshop.

We will be using Python 3.6, and the environment will be an **Anaconda Environment**.
The installation takes considerable amounts of time (up to 10min), especially if the network bandwidth is limited, so **PLEASE** don't try doing it during the workshop.

There is also an alternative (http://mybinder.org), however we cannot guarantee its reliability -- if you have the option, go with the Anaconda Environment.


## Configure your environment with Anaconda

First, you need to install [miniconda](https://conda.io/miniconda.html).

Next, to actually create the environment (named `workshop`), type:
```
conda env create -f environment.yml
```

To activate the environment, type:
```
source activate workshop
```

Once you'll get access to the workshop materials, you'll be asked to go to the cloned workshop directory, and initialize a notebook by calling:
```
jupyter-notebook
```

And once the workshop is over, you can deactivate the environment by typing:
```
source deactivate
```

See the [Anaconda docs](http://conda.pydata.org/docs) for more.


## Alternatively

You might try out a fairly new service (http://mybinder.org) and type in the workshop's URL (which will be http://github.com/nethone/keystroke-dynamics once it will be made public), choose branch `master`, and type in the relevant notebook file name: `"workshop.ipynb"`.

