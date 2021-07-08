========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/forger/badge/?style=flat
    :target: https://forger.readthedocs.io/
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/FarhadMaleki/forger.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/FarhadMaleki/forger

.. |version| image:: https://img.shields.io/pypi/v/forger.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/forger

.. |wheel| image:: https://img.shields.io/pypi/wheel/forger.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/forger

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/forger.svg
    :alt: Supported versions
    :target: https://pypi.org/project/forger

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/forger.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/forger

.. |commits-since| image:: https://img.shields.io/github/commits-since/FarhadMaleki/forger/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/FarhadMaleki/forger/compare/v0.0.0...master



.. end-badges

A package for 3D image augmentation

* Free software: GNU Lesser General Public License v3 (LGPLv3)

Installation
============

::

    pip install forger

You can also install the in-development version with::

    pip install https://github.com/FarhadMaleki/forger/archive/master.zip


Documentation
=============


https://forger.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
