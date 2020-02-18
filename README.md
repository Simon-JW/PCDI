# Instructions on how to setup and run the algorithm desribed in "A multi-resolution method to map and identify locations of future gully and channel incision".

The algorithm was written using an Anconda 3.7 (https://www.anaconda.com/distribution/) installation with the following required dependencies:

GDAL: https://anaconda.org/conda-forge/gdal

xarray: https://anaconda.org/anaconda/xarray

Landlab: http://landlab.github.io/#/

All of the above can be installed using the conda package manager.

An additional unrequired package that the program imports by default is jupyterthemes (https://github.com/dunovank/jupyter-themes). If you don't want the option of changing themes then you can simply delete the first two lines from the "Imports" code block.

Data to test the algorithm is available here https://elevation.fsdf.org.au/

File reading and writing is setup assuming inputs are in standard Geotiff format.
