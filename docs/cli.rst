=========
CLI Usage
=========

.. highlight:: none

.. NOTE:: To use the CLI, install with the extra ``cli`` (e.g. ``pip install callooktools[cli]``) or otherwise install the library ``rich``.

``callooktools`` has a basic CLI interface, which can be run using:

.. code-block:: sh

    $ python3 -m callooktools

It can be used with the following arguments::

    usage: callooktools [-h] [--no-pretty] CALL [CALL ...]

    Retrieve callsign data from callook.info.

    positional arguments:
      CALL         The callsign(s) to look up

    optional arguments:
      -h, --help   show this help message and exit
      --no-pretty  Don't pretty-print output
