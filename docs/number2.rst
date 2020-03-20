File number2

Code block - literal
====================

This is a normal text paragraph. The next paragraph is a code sample::

  POST http://localhost:8000/VPE/session/login/
  Content-Type: application/json
  {
    "ChangePassword": true,
    "Username": "admin",
    "Password": "********",
    "NewPassword": "New$*Password43"
  }

Tabs
====
.. container:: content-tabs class

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
        :title: Tab title two

.. code-block:: javascript

  POST http://localhost:8000/VPE/session/login/
  Content-Type: application/json
  {
    "ChangePassword": true,
    "Username": "admin",
    "Password": "********",
    "NewPassword": "New$*Password43"
  }


code-block directive
====================

.. code-block:: javascript

  POST http://localhost:8000/VPE/session/login/
  Content-Type: application/json
  {
    "ChangePassword": true,
    "Username": "admin",
    "Password": "********",
    "NewPassword": "New$*Password43"
  }
