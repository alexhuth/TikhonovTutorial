# TikhonovTutorial
Originally given as a tutorial at NeuroHackademy 2020 by Alex Huth. [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexhuth/tikhonovtutorial/master)

In this tutorial you'll learn about three different linear regression methods: ordinary least squares, ridge regression, and Tikhonov regression. The tutorial explores these methods both theoretically and practically, since each is used to fit encoding models that predict fMRI responses to natural language stimuli.

This tutorial has three parts:
* `1_tikhonov_tutorial.ipynb` - this part covers ordinary least squares (OLS) and introduces the fMRI encoding analysis
* `2_tikhonov_tutorial.ipynb` - this part covers ridge regression
* `3_tikhonov_tutorial.ipynb` - this part covers Tikhonov regression

#### Acknowledgements
The fMRI data used in this tutorial was collected by Alex Huth and Wendy de Heer at the University of California, Berkeley. Much of the theory work was done in concer with Anwar Nunez. All work was supervised by professors Jack Gallant and Frederic Theunissen of the UC Berkeley Psychology Department. Visualization is done using [pycortex](http://pycortex.org).

#### Citation
The analysis demonstrated in this tutorial forms the basis of these two papers:
* [Nunez-Elizalde, A. O. et al., "Voxelwise encoding models with non-spherical multivariate normal priors" (2019) _NeuroImage_.](https://www.sciencedirect.com/science/article/abs/pii/S1053811919302988)
* [Huth, A. G. et al., "Natural speech reveals the semantic maps that tile human cerebral cortex" (2016) _Nature_.](https://www.nature.com/articles/nature17637)

Getting Started
---------------
There are two ways you can run this tutorial. If you want to go through the materials on your own machine, please follow the instructions below:

_On Linux_

1. (If not using Anaconda) install dependencies:
`sudo apt-get update`
`sudo apt-get install -y ipython ipython-notebook python-numpy python-scipy python-matplotlib cython python-pip python-pip python-dev python-h5py python-nibabel python-lxml python-shapely python-html5lib python-tables git pycortex`
2. Start a Jupyter notebook server in this directory (if you don't already have one):
`jupyter notebook`

OR

1. `git clone https://github.com/alexhuth/TikhonovTutorial`
2. `cd TikhonovTutorial`
3. `pip install -r requirements.txt`
4. `jupyter notebook`


If you want to run it interactively in your browser without the necessity to install the dependencies, please check this binder instance:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexhuth/tikhonovtutorial/master)

The necessary fMRI data will be downloaded and unarchived in the first tutorial notebook, so make sure you run that before the others!
