django-pageguide
================

Django integration with `pageguide`_, an interactive guide for web page elements

.. _pageguide: https://github.com/tracelytics/pageguide

Installation
============

Put the `pageguide` app In your `settings.py`:
----------------------------------------------

::

    INSTALLED_APPS = (
        'django.contrib.auth',
        'django.contrib.contenttypes',
        'django.contrib.sessions',
        'django.contrib.sites',
        'django.contrib.admin',

        #.....................#

        'pageguide',
    )


Run the migrations:
-------------------

::

    >>> python manage.py syncdb


Integrate in your base template:
--------------------------------

::

    COMPLETE


Development
===========

You can get the last bleeding edge version of django-pageguide by doing a clone
of its git repository::

  git clone https://github.com/msaelices/django-pageguide.git
