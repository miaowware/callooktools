=====
Types
=====

.. WARNING:: This library is now deprecated. Use `callsignlookuptools <https://pypi.org/project/callsignlookuptools/>`_ instead.

.. highlight:: none

.. module:: callooktools.callooktools

Callsign Data
=============

.. autoclass:: CallookCallsignData()
    :exclude-members: grant_date, expire_date, address, latlong, grid, mod_date

    .. autoattribute:: address
        :annotation: : Address = Address()

    .. autoattribute:: latlong
        :annotation: : LatLong = LatLong(0, 0)

    .. autoattribute:: grid
        :annotation: : Grid = Grid(LatLong(0, 0))

    .. autoattribute:: grant_date
        :annotation: : datetime.datetime = datetime.datetime.min

    .. autoattribute:: expire_date
        :annotation: : datetime.datetime = datetime.datetime.min

    .. autoattribute:: mod_date
        :annotation: : datetime.datetime = datetime.datetime.min

Helper Data Types
=================

.. autoclass:: Address()

.. autoclass:: LicenseType()

.. autoclass:: LicenseClass()

.. autoclass:: EntryStatus()

Exceptions
==========

.. autoclass:: CallookError
