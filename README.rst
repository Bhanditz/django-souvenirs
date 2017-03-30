================
Django Souvenirs
================

|PyPI| |Build Status| |Coverage Report|

Souvenirs is a Django app for efficiently tracking user activity.

|Souvenirs Album Cover|

Installation
------------

To get the latest stable release from PyPi

.. code-block:: bash

    pip install django-souvenirs

Or get the latest commit from GitHub

.. code-block:: bash

    pip install -e git+git://github.com/appsembler/django-souvenirs.git#egg=souvenirs

Add to ``settings.INSTALLED_APPS``

.. code-block:: python

    INSTALLED_APPS = [
        ...,
        'souvenirs',
    ]

Add to ``settings.MIDDLEWARE_CLASSES``

.. code-block:: python

    MIDDLEWARE_CLASSES = [
        ...,
        'souvenirs.middleware.SouvenirsMiddleware',
    ]

Migrate your database

.. code-block:: bash

    ./manage.py migrate souvenirs

Usage
-----

configuration, api

Legal
-----

Copyright 2017 `NodeRabbit Inc., d.b.a. Appsembler <https://appsembler.com>`_

Released under the `MIT license <https://github.com/appsembler/django-souvenirs/blob/master/LICENSE>`_

.. _PyPI: https://pypi.python.org/pypi/django-souvenirs

.. |Build Status| image:: https://img.shields.io/travis/appsembler/django-souvenirs/master.svg?style=plastic
   :target: https://travis-ci.org/appsembler/django-souvenirs?branch=master

.. |Coverage Report| image:: https://img.shields.io/codecov/c/github/appsembler/django-souvenirs/master.svg?style=plastic
   :target: https://codecov.io/gh/appsembler/django-souvenirs/branch/master

.. |PyPI| image:: https://img.shields.io/pypi/v/django-souvenirs.svg?style=plastic
   :target: PyPI_

.. |Souvenirs Album Cover| image:: https://images-na.ssl-images-amazon.com/images/I/51UhpUAIRaL._SS500.jpg
   :target: https://www.amazon.com/Souvenirs-Reinhardt-Quintet-St%C3%A9phane-Grappelli/dp/B000VWONGE
