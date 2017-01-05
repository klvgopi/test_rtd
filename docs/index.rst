.. gt_RTD documentation master file, created by
   sphinx-quickstart on Wed Jan  4 19:42:06 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to gt_RTD's documentation!
==================================

a test documentation for *cassandra*. link1 : google_ . link2: `install app`_

.. _google: http://google.com
.. _install app: http://yoututbe.com


Indices and tables
------------------

There are 3 main sections in this.

* :ref: sec1
* :ref: sec2
* :ref: sec3
* :ref: `sec4`


.. _sec1:
.. toctree::
   :maxdepth: 2
   :caption: Contents: Section1 start

	subsec1
	subsec2

.. _sec2:
.. toctree::
   :maxdepth: 2
   :caption: Contents: Section2 start

	subsec3

.. _sec3:
.. toctree::
   :maxdepth: 2
   :caption: Contents: Section3 start

	subsec4

.. _sec4:
.. toctree::
   :maxdepth: 2
   :caption: Contents: Section4 start

	subsec5


.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Contents: Section5 start

	subsec6
	gtdir2/*
	gtdir/subsec17


THE END


