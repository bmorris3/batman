.. _installation:

Installation
============
pip
---
You can install ``robin`` with pip (recommended):

::

	$ pip install robin-package

From source
-----------
You can also install directly from source. The most current `stable release <https://pypi.python.org/pypi/robin-package/>`_ is up on PyPI and the `development version <https://github.com/bmorris3/robin>`_ can be found on GitHub.


Unpack the distribution with ``tar -xvf`` and navigate to the source root directory.  To install, run the setup script:

::

   $ sudo python setup.py install

Note that you'll need to ``cd`` out of the source directory **before** you can import ``robin``.

On Windows
----------
Some intrepid users have braved the path of installing batman on Windows. Their advice is available on the `issue tracker <https://github.com/lkreidberg/batman/issues/26>`_.

Tests
-----
To check whether the install is working, I recommend running a few basic tests with:

::

	$ python -c 'import robin; robin.test()'


