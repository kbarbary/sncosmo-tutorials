# sncosmo-tutorials

This is a tutorial on [sncosmo](http://sncosmo.readthedocs.io) for the
LSST DESC SN workshop 16 - 18 November 2016.

Dependencies
------------

The notebooks are written assuming sncosmo v1.4.0.

Assuming you have numpy, scipy, matplotlib and astropy installed...

**Using conda**

```
conda install -c astropy sncosmo iminuit emcee
```

**Using pip**

```
pip install sncosmo iminuit emcee
```

To check that you have the right version, start python and do

```python
>>> import sncosmo
>>> sncosmo.__version__
'1.4.0'
```