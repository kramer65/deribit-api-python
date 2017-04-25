API Client from Deribit API
===========================

API client for `Deribit API`_. 

Full documentation is available at `https://github.com/deribit/deribit-api-python`_.

Simple example:
::

    from deribit_api import RestClient
    client = RestClient("KEY", "SECRET")
    client.index()
    client.account()

.. _`Deribit API`: https://www.deribit.com/docs/api/
.. _`https://github.com/deribit/deribit-api-python`: https://github.com/deribit/deribit-api-python