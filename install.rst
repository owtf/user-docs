Installation
============

Prerequisites
-------------

There are few packages which are mandatory before you proceed

    * Git client: ``sudo apt-get install git``
    * Python 2.7, installed by default in most systems
    * Wget: ``sudo apt-get install wget``

Installation Methods
--------------------

There are two ways in which you can proceed. Both the methods execute the install script:

    .. toctree::
       :maxdepth: 2

       installation/methods.rst

Install Script
^^^^^^^^^^^^^^

The install script :

    * Prompts you to select a distro from a list containing supported distros

    .. note::
        If your distro is not listed in supported distros, please go through Advanced Installation method.

    * Installs some tools, dictionaries and configration files
    * Installs python libraries using ``pip``

.. include:: installation/advanced.rst
