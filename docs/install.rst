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
required to handle the hierarchical structures.

Python
************

Probably, unless you are working with Linux and you can use some
package manager like `Synaptic`, the easy way to have Python up and
running on your system is to use `Anaconda`
(`https://www.anaconda.com/ <https://www.anaconda.com/>`_). Therefore,
download and install the Python (version 3.X) of Anaconda which is
suitable for your OS by following the instruction provided on the
Anaconda web site.

The `anytree` module
*************************

Some capabilities of `hiegeo` are provided by the Python `anytree`
module (`https://pypi.org/project/anytree/
<https://pypi.org/project/anytree/>`_). Once installed Anaconda, you can open the `Anaconda prompt` and install it by typing::

    pip install anytree


To verify if the installation worked properly, you can open a Python
shell and check that the line :code:`import anytree` works and does not
provide any error output.
    


The `hiegeo` module
*********************

If you keep the provided module file (``hiegeo.py``) in the same
directory of the calling script, then everything should work as it is.

Alternatively, if you prefer to have more flexibility, you can put the
file ``hiegeo.py`` in a directory that should be included in your
``PYTHONPATH`` environmental variable. If you are using the editor
`Spyderlib`, included in Anaconda, to do that you can use the ``Python
Path Manager``; in that case you will need to **restart** Spyderlib.


Verification
-----------------

In the end, to verify if ``hiegeo`` was properly installed and
available to your Python script, you can call it from the Python shell with

.. sourcecode:: python
  
    include hiegeo

to double check is any error rises.




