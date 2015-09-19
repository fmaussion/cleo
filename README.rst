.. -*- rst -*- -*- restructuredtext -*-
.. This file should be written using restructured text conventions

====
Cleo
====

.. image:: https://travis-ci.org/fmaussion/cleo.svg?branch=master
    :target: https://travis-ci.org/fmaussion/cleo

.. image:: https://coveralls.io/repos/fmaussion/cleo/badge.svg?branch=master&service=github
  :target: https://coveralls.io/github/fmaussion/cleo?branch=master

Cleo is a `cat <https://drive.google.com/file/d/0B-0AsTwFw61uRnZZY1l4cjU2b3M
/view?usp=sharing>`_. Cleo is also a small library to visualize georeferenced
data.


Installation
------------

Cleo builds upon the companion project `Salem <https://github
.com/fmaussion/salem>`_ and has the same dependencies.

After installing the required packages, a simple `pip install` should be
enough::

    $ pip install git+https://github.com/fmaussion/cleo.git#egg=Cleo


Classes
-------

**DataLevels**
    Associate the right color to the data according to user specifications.
    It is useful because it prevents any mismatch between plot and colorbar
    by managing both concepts together and not separated as matplotlib does.

**Map**
    A cartographic representation of georeferenced 2D data. Handles country
    borders, all kinds of geometries, topographical shading, and map
    projections.

About
-----

:License:
    GNU GPLv3

:Author:
    Fabien Maussion - fabien.maussion@uibk.ac.at
