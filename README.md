
# ncplot - Automatic interactive plotting of NetCDF files in Python 



[![pypi](https://img.shields.io/pypi/v/ncplot.svg)](https://pypi.python.org/pypi/ncplot/)
[![Documentation Status](https://readthedocs.org/projects/ncplot/badge/?version=latest)](https://ncplot.readthedocs.io/en/latest/?badge=latest)


An easy to use Python (3.6 and above) package for quickly plotting the contents of NetCDF files or xarray datasets in Python or on the command line. 

This package is designed to work with [CF](https://cfconventions.org/) compliant NetCDF data. 

## Installation

To install from pypi:
```sh
pip install ncplot 
```

Install the development version using using pip:
```sh
pip install git+https://github.com/pmlmodelling/ncplot.git
```


## How to use in Python


The package is made up of a simple easy to use function: ncplot. To visualize everything in a file:

```sh
from ncplot import ncplot

ncplot("example.nc")

```

or to visualize a specific variable or list of variables:

```sh
from ncplot import ncplot

ncplot("example.nc", vars)

```

where vars is a string representing a variable or a list of variables.




## How to use on the command line

Command line usage is as simple as:


```sh


ncplot example.nc

```








# Reference and tutorials

A full API reference, and a how-to guide are available at [readthedocs](https://ncplot.readthedocs.io/en/latest/).








