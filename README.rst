========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-local-github-repo-config/badge/?style=flat
    :target: https://readthedocs.org/projects/python-local-github-repo-config
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/techdragon/python-local-github-repo-config.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/python-local-github-repo-config

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/python-local-github-repo-config?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/python-local-github-repo-config

.. |requires| image:: https://requires.io/github/techdragon/python-local-github-repo-config/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/python-local-github-repo-config/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/techdragon/python-local-github-repo-config/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/techdragon/python-local-github-repo-config

.. |codecov| image:: https://codecov.io/github/techdragon/python-local-github-repo-config/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/python-local-github-repo-config

.. |landscape| image:: https://landscape.io/github/techdragon/python-local-github-repo-config/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/python-local-github-repo-config/master
    :alt: Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/techdragon/python-local-github-repo-config/badges/gpa.svg
   :target: https://codeclimate.com/github/techdragon/python-local-github-repo-config
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/local-github-repo-config.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/local-github-repo-config

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/python-local-github-repo-config/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/python-local-github-repo-config/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/local-github-repo-config.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/local-github-repo-config

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/local-github-repo-config.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/local-github-repo-config

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/local-github-repo-config.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/local-github-repo-config

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/techdragon/python-local-github-repo-config/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/techdragon/python-local-github-repo-config/


.. end-badges

Provides access to a local GitHub repository's configuration.

* Free software: MIT license

Installation
============

::

    pip install local-github-repo-config

Documentation
=============

https://python-local-github-repo-config.readthedocs.io/

Development
===========

To run the all tests run::

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
