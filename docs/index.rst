.. bplib documentation master file, created by
   sphinx-quickstart on Sun Dec 25 06:07:20 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to bplib's documentation!
=================================

.. automodule:: bplib

Reference
=========

Module bplib.bp.BpGroup
-----------------------
 
.. autoclass:: bplib.bp.BpGroup
    :members:

Module bplib.bp.GXElem
-----------------------

.. autoclass:: bplib.bp.G1Elem
    :members:

.. autoclass:: bplib.bp.G2Elem
    :members:

.. autoclass:: bplib.bp.GTElem
    :members:


Encoding and decoding bplib objects
-----------------------------------

The ``petlib.pack`` functions ``encode`` and ``decode`` may be used to get byte representations of ``BpGroup``, ``G1Elem``, ``G2Elem``, and ``GTElem``. Just ensure you import ``bplib`` before calling those functions.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

