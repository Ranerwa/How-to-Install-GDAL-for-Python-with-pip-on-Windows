# How-to-Install-GDAL-for-Python-with-pip-on-Windows

I have been struggling to install gdal package for python with pip on windows.
you can not just input pip install gdal on python console.


Here you can use this way:

>>>conda create -n gdalpip python=3.9

>>>conda activate gdalpip

####Go to the website https://www.lfd.uci.edu/~gohlke/pythonlibs/#gdal, and download a suitabe version. 

>>>cd Downloads

>>>python -m pip install GDAL-3.4.3-cp311-cp311-win_amd64.whl

Now you can check!

>>> from osgeo import gdal

>>> from osgeo import ogr

>>> from osgeo import osr
