Learner Fork
============

This is my fork of the repo that contains the changes I made as I was going through it to learn.

Notes
-----
To make my docs I run::
    sphinx-apidoc --force --separate --no-toc -o source/ ../src/crawler/
    make clean
    make html

in ``crawler/andy_docs``

I added ``crawler/andy_docs`` to the ``exclude_patterns`` in ``conf.py`` to stop loads of duplicate reference errors. Theres still some errors when I run ``make html`` in the root of the repo (to build the tutorial docs) but they're there if you build in a fresh clone - so I'm leaving them :).

Useful Resources
----------------
http://sphinx-argparse.readthedocs.io/en/latest/index.html - for generating cli docs
http://autoapi.readthedocs.io/ - for prettier API documentation
https://kev.inburke.com/kevin/sphinx-interlinks/ - Creating links within your docs
https://gisellezeno.com/tutorials/sphinx-for-python-documentation.html - Brief intro to running Sphinx


The original readme continues below.


---------------------------------------------------------------------

Sphinx Tutorial
===============

Welcome to the Introduction to Sphinx & Read the Docs.
This tutorial will walk you through the initial steps 
writing reStructuredText and Sphinx,
and deploying that code to Read the Docs.

Please provide feedback to `@ericholscher`_.

.. _@ericholscher: http://twitter.com/ericholscher

Schedule
--------

* 9-9:30 Introduction to the Tutorial
* 9:30-9:50 :doc:`start`
* 9:50-10:20 :doc:`step-1`
* 10:20-10:40 *Break*
* 10:40-11:10 :doc:`step-2`
* 11:10-11:40 :doc:`step-3`
* 11:40-12:20 :doc:`finish`

Thanks for coming

.. toctree::
   :maxdepth: 2
   :caption: Tutorial

   start
   step-1
   step-2
   step-3
   finish

.. toctree::
   :maxdepth: 2
   :caption: Supplemental Material 

   cheatsheet

.. toctree::
   :caption: Step 1
   :glob:

   crawler/docs/step1/index

.. toctree::
   :caption: Step 2
   :glob:

   crawler/docs/step2/index
  
.. toctree::
   :caption: Step 3
   :glob:

   crawler/docs/step3/index
 
  
