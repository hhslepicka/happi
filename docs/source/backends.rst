Supported Backends
##################

All backends inherit from the following metaclass

.. autoclass:: happi.backends.core._Backend
   :members:

Backend Choices
^^^^^^^^^^^^^^^
.. autosummary::
   :toctree: generated

   happi.backends.mongo_db.MongoBackend
   happi.backends.json_db.JSONBackend
   happi.backends.qs_db.QSBackend
