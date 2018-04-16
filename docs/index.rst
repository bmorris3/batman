.. robin documentation master file, created by
   sphinx-quickstart on Tue Jun 16 12:35:22 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. |br| raw:: html

   <br />

robin: ROBust exoplanet radii from INgress/egress durations
===========================================================

Welcome to the documentation for ``robin``, a Python package for fast calculation
of exoplanet transit light curves.  The package supports calculation of light
curves for any radially symmetric stellar limb darkening law, using the
`batman integration algorithm <http://adsabs.harvard.edu/abs/2015PASP..127.1161K>`_
for models that cannot be quickly calculated analytically.

In typical use, ``robin`` can calculate a million model light curves in well
under 10 minutes for any limb darkening profile.

Contents:

.. toctree::
   :maxdepth: 2

   installation
   quickstart
   tutorial
   api
   trouble 
   acknowledgements

Release Notes
-------------
.. include::  ../changelog.rst


