Ndarrayarray
============

This package enables you to work with a disk-based, memory mapped array of NumPy numeric
ndarrays, each of which may have an arbitrary number of dimensions and shape.

It is an extension of the concept of a ragged (or 'jagged') array, which is an array of arrays
with different lengths, and is convenient when you want to store and retrieve a large sequence
of numpy arrays with variable shapes.

Since ndarrayarrays are memory-mapped from disk they can be larger than RAM.

The Ndarrayarray package depends on the `Darr <https://github.com/gbeckers/Darr/>`__ package.

