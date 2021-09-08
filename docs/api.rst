=============
API Reference
=============

.. WARNING:: This library is now deprecated. Use `callsignlookuptools <https://pypi.org/project/callsignlookuptools/>`_ instead.

.. highlight:: none

``callooktools`` allows for both synchronous and asynchronous usage via two main classes, :class:`callooktools.CallookSync` and :class:`callooktools.CallookAsync`.
These inherit from :class:`callooktools.CallookAbc`. See there for some properties.

.. module:: callooktools

.. autoclass:: CallookAbc
    :exclude-members: get_callsign

Synchronous
===========

.. autoclass:: CallookSync

Asynchronous
============

.. autoclass:: CallookAsync
