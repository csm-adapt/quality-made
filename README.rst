===========
QualityMade
===========

Welcome to the Quality Made GitHub repo! This is meant to provide a place for
the participants in the Navy Quality Made team to share their code.


Description
===========

First, a quick tour of the structure of this repository, in what is (perhaps
a vain) hope to maintain some order and make sure others can find and reuse
your work.


Best Practices
--------------

**Please document your work using the native mechanism for your programming
language of choice.** For example, Python docstrings on all functions, classes,
and modules; or Matlab help text (comment lines) after function, class
definitions, class properties, etc.

**Code goes in src/.** :literal:`src` is divided by language to make it easier
for people familiar with one language or another. If your language isn't there,
e.g. ruby or scala, please add it! Within each language folder is a folder for
common tasks:

* classification

* clustering

* regression

* scripts

* visualization

:literal:`scripts` is a place to put more fully developed scripts or jupyter
notebooks. Since these will often read in data, please place that data in the
:literal:`scripts/data` folder, so others have the data upon which your script
depends.

While there is no :literal:`scratch` or :literal:`misc`, since they
too often become the catch-all, there may be very legitimate reasons for such
folders. However, please help your fellow developers by putting your
functions/modules in the most appropriate folder. If there is another
classification that better describes your code--please add it.


Closing Remarks
===============

Thank you all for contributing! If you add something to this repo, please add
your name to the :literal:`AUTHORS.rst`. Not only do you get credit for your
hard work, but we also know who to contact with questions, comments, praise
and adulation.


Note
====

This project has been set up using PyScaffold 3.0.3. For details and usage
information on PyScaffold see http://pyscaffold.org/.
