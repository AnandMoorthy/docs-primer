Include the following code in your program to create a client
connection to a running :program:`mongod` instance and use the
``test`` database.

.. code-block:: cpp

   mongocxx::instance inst{};
   mongocxx::client conn{};

   auto db = conn["test"];


