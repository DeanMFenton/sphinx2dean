Main page
=========

File tabs test

Tabs
====
.. container:: content-tabs

.. tab-container:: tab1
        :title: Java

.. code-block:: javascript

  POST http://localhost:8000/VPE/session/login/
  Content-Type: application/json
  {
    "ChangePassword": true,
    "Username": "admin",
    "Password": "********",
    "NewPassword": "New$*Password43"
  }

.. tab-container:: tab2
        :title: Python

.. code-block:: javascript

  POST http://localhost:8000/VPE/session/login/
  Content-Type: application/json
  {
    "ChangePassword": true,
    "Username": "admin",
    "Password": "********",
    "NewPassword": "New$*Password43"
  }
