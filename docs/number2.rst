File number2

Code blocks
===========

This is a normal text paragraph. The next paragraph is a code sample::

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

.. code-block:: JSON

POST http://localhost:8000/VPE/session/login/
  Content-Type: application/json
  {
    "ChangePassword": true,
    "Username": "admin",
    "Password": "********",
    "NewPassword": "New$*Password43"
  }
