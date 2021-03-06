{{cookiecutter.project_name}}
*******************************************************

`Docs`_

.. image:: https://travis-ci.org/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}.svg?branch=master
    :target: https://travis-ci.org/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}
    :alt: Build Status
.. image:: https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}
    :alt: Code Coverage
.. image:: https://readthedocs.org/projects/{{cookiecutter.project_name}}/badge/?version=latest
    :target: http://{{cookiecutter.project_name}}.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status
.. image:: https://badge.fury.io/py/{{cookiecutter.project_name}}.svg
    :target: https://badge.fury.io/py/{{cookiecutter.project_name}}
    :alt: PyPi Version
.. image:: https://img.shields.io/badge/python-3.6-blue.svg
    :target: https://badge.fury.io/py/pdfebc
    :alt: Supported Python Versions

.. contents::

Overview
========
{{cookiecutter.description}}

Requirements
============
To be added ...

Install
=======
Option 1: Install from PyPi with ``pip``
----------------------------------------
The latest release of ``{{cookiecutter.project_name}}`` is on PyPi, and can thus be installed as usual with ``pip``.
I strongly discourage system-wide ``pip`` installs (i.e. ``sudo pip install <package>``), as this
may land you with incompatible packages in a very short amount of time. A per-user install
can be done like this:

1. Execute ``pip install --user {{cookiecutter.project_name}}`` to install the package.
2. Further steps to be added ...


Option 2: Clone the repo and the install with ``pip``
-----------------------------------------------------
If you want the dev version, you will need to clone the repo, as only release versions are uploaded
to PyPi. Unless you are planning to work on this yourself, I suggest going with the release version.

1. Clone the repo with ``git``:
    - ``git clone https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}``
2. ``cd`` into the project root directory and install with ``pip``.
    - ``pip install --user .``, this will create a local install for the current user.
    - Or just ``pip install .`` if you use ``virtualenv``.
    - For development, use ``pip install -e .`` in a ``virtualenv``.
3. Further steps to be added ...
   
How to run
==========
Assuming everything is installed correctly, running the application is dead simple.

1. Execute ``{{cookiecutter.project_name}} runserver -h x.x.x.x -p n`` to run ``pdfebc-web`` 
   where ``x.x.x.x`` is the hostname and ``n`` is the port. 
2. Further steps to be added ...

License
=======
This software is licensed under the MIT License. See the `license file`_ file for specifics.

Contributing
============
To be added ...

.. _license file: LICENSE
.. _sample configuration: config.cnf
.. _requirements.txt: requirements.txt
.. _Docs: https://{{cookiecutter.project_name}}.readthedocs.io/en/latest/
