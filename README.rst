MultipleImageIterator
==============================

.. image:: https://github.com/KitwareMedical/MultipleImageIterator/workflows/Build,%20test,%20package/badge.svg

Overview
--------

An `ITK <https://itk.org>`_-based implementation of principal components analysis.

For more information, see the `Insight Journal article <https://hdl.handle.net/10380/3455>`_::

  Schaerer J.
  A MultipleImageIterator for iterating over multiple images simultaneously
  The Insight Journal. December, 2014.
  https://hdl.handle.net/10380/3455
  https://www.insight-journal.org/browse/publication/915

Installation
------------

Since ITK 4.11.0, this module is available in the ITK source tree as a Remote
module. To enable it, set::

  Module_MultipleImageIterator:BOOL=ON

in ITK's CMake build configuration.

License
-------

This software is distributed under the Apache 2.0 license. Please see
the *LICENSE* file for details.
