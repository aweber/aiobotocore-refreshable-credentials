aiobotocore-refreshable-credentials
===================================
Implements an aiobotocore.Session subclass for using aiobotocore with expiring
credentials (IAM STS).

|Version| |Status| |Coverage| |License|

Usage
=====

.. code:: python

    import aiobotocore_refreshable_credentials

    session = aiobotocore_refreshable_credentials.get_session()
    async with session.create_client('rekognition') as client:
        ...


Python Versions Supported
-------------------------
3.8+

.. |Version| image:: https://img.shields.io/pypi/v/aiobotocore-refreshable-credentials.svg?
   :target: https://pypi.python.org/pypi/aiobotocore-refreshable-credentials

.. |Status| image:: https://github.com/aweber/aiobotocore-refreshable-credentials/workflows/Testing/badge.svg?
   :target: https://github.com/aweber/aiobotocore-refreshable-credentials/actions?workflow=Testing
   :alt: Build Status

.. |Coverage| image:: https://img.shields.io/codecov/c/github/aweber/aiobotocore-refreshable-credentials.svg?
   :target: https://codecov.io/github/aweber/aiobotocore-refreshable-credentials?branch=master

.. |License| image:: https://img.shields.io/pypi/l/aiobotocore-refreshable-credentials.svg?
