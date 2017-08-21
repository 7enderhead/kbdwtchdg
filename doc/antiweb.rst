*********************
Extract documentation
*********************

A tool called `antiweb <https://github.com/7enderhead/antiweb>`_ can extract ``.rst`` files for use with `Sphinx <http://sphinx-doc.org/>`_ from comments in your code.

Installation
============

You can use ``pip install antiweb`` to get the latest version of antiweb. 

Usage
=====

You need to set special `directives <http://antiweb.readthedocs.io/en/latest/getting_started.html>`_ inside your comments. Those are being
interpreted by antiweb.

To generate the `.rst` file, navigate to the folder where ``main.c`` (or your source file) is located and type:

 ``antiweb <source file> <options>``

In this case ``antiweb main.c``. That will generate a file called main.rst which can then be used by Sphinx for documentation.

More information
================

If you want to learn more about antiweb and its usage, click `here <http://antiweb.readthedocs.io/en/latest/>`_.