========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-cftotf/badge/?style=flat
    :target: https://python-cftotf.readthedocs.io/
    :alt: Documentation Status

.. |version| image:: https://img.shields.io/pypi/v/cftotf.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/cftotf

.. |wheel| image:: https://img.shields.io/pypi/wheel/cftotf.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/cftotf

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/cftotf.svg
    :alt: Supported versions
    :target: https://pypi.org/project/cftotf

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/cftotf.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/cftotf

.. |commits-since| image:: https://img.shields.io/github/commits-since/tsenay/python-cftotf/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/tsenay/python-cftotf/compare/v0.1.0...master



.. end-badges

Convert cloudformation template to terraform module

* Free software: BSD 2-Clause License

Installation
============

::

    pip install cftotf

You can also install the in-development version with::

    pip install https://github.com/tsenay/python-cftotf/archive/master.zip


Documentation
=============


https://python-cftotf.readthedocs.io/


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
