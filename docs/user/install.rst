.. _install:

Installation
============

This part of the documentation covers the installation of dbConnect.


Requirements
------------

dbConnect uses `mysql.connector` and `mysqlclient` for mysql, install **one** of them using::

    $ apt-get install python3-mysql.connector
    $ apt-get install python-mysql.connector

    $ pip install mysqlclient

For PostgreSQL install psycopg2 module::

    $ pip install psycopg2

Distribute & Pip
----------------

Installing dbConnect is simple with `pip <https://pip.pypa.io>`_, just run
this in your terminal::

    $ pip install dbConnect

or, with `easy_install <http://pypi.python.org/pypi/setuptools>`_::

    $ easy_install dbConnect

But, you really `shouldn't do that <https://stackoverflow.com/questions/3220404/why-use-pip-over-easy-install>`_.


Get the Code
------------

dbConnect is actively developed on Gitlab, where the code is
`always available <https://gitlab.com/mastizada/dbConnect>`_.

You can either clone the public repository::

    $ git clone git@gitlab.com:mastizada/dbConnect.git

Once you have a copy of the source, you can embed it in your Python package,
or install it into your site-packages using::

    $ python setup.py install
