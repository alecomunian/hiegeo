Installation
========================

Installing and using `hiegeo` should be relatively easy, and thanks to
Python's flexibility, that should be feasible on many operative
systems (OSs), including MS Windows, Mac OS X and Linux.

Requirements
-----------------------

To use the `hiegeo` module you need a standard Python3.X installation,
together with the main mathematical and plotting libraries (``numpy``,
``pandas``, ``matplotlib`` etc) and the module ``anytree``, which is
required to handle the hierarchical structures. If ``pip`` is used for
the installation, all there requirement should be automatically
satisfied.

Python
************

Probably, unless you are working with Linux and you can use some
package manager like `Synaptic`, the easy way to have Python up and
running on your system is to use `Anaconda`
(`https://www.anaconda.com/ <https://www.anaconda.com/>`_). Therefore,
download and install the Python (version 3.X) of Anaconda which is
suitable for your OS by following the instruction provided on the
Anaconda web site.

Install `hiegeo`
-----------------------

The suggested way is to use ``pip`` (which should be also already
available with `Anaconda`).

1) Clone or download the repository on your hard drive.
2) If required, unpack it and enter the folder with ``cd hiegeo``.
3) Inside the project directory, from the command line::

     pip install -e .

4) To check if it worked, open a Python terminal and try::

     import hiegeo





