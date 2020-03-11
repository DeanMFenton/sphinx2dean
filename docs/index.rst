.. sphinx documentation master file, created by
   sphinx-quickstart on Tue Mar 10 11:11:04 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Dean's Sphinx2 documentation
===========================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. My stuff next

This is a normal text paragraph. The next paragraph is a code sample::

  POST http://localhost:8000/VPE/session/login/
  Content-Type: application/json
  {
    "ChangePassword": true,
    "Username": "admin",
    "Password": "********",
    "NewPassword": "New$*Password43"
  }


Tables
======

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

Link
====

`Link text <https://www.hcc-embedded.com/>`_

Asterisks
=========
*italics*
**bold**
``code``

* bullet list
* bullet 2

1. numbered
2. hhhh

| These lines are
| broken exactly like in
| the source file.
