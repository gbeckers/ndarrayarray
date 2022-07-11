Ndarrayarray
============

|Repo Status|

This package enables you to work with a disk-based, memory mapped array of NumPy numeric
ndarrays, each of which may have an arbitrary number of dimensions and shape.

It extends the concept of a ragged (or 'jagged') array, which is an array of arrays
with different lengths, to an array of arrays with any dimensionality and shape.

Since ndarrayarrays are memory-mapped from disk they can be (much) larger than RAM.

The Ndarrayarray package depends on the `Darr <https://github.com/gbeckers/Darr/>`__ package.

Ndarrayarray is very early in development. It is open source and freely available under
the `New BSD License <https://opensource.org/licenses/BSD-3-Clause>`__ terms.

Ndarrayarray is BSD licensed (BSD 3-Clause License). (c) 2022, Gabriël
Beckers

.. |Repo Status| image:: https://www.repostatus.org/badges/latest/wip.svg
   :alt: Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.
   :target: https://www.repostatus.org/#wip

