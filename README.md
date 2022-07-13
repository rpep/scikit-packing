# scikit-packing

A collection of algorithms for packing and covering problems in Python

## Motivation

Packing problems come up in all sorts of areas - fitting objects into boxes
when moving home, scheduling deliveries and more. There are a wide range of
different approximate algorithmic approaches to this, from linear programming
to stochastic approaches. The dual of this problem covering problems. 

This package aims to provide a set of implementations of common algorithms. We
don't necessarily aim to be the best performing implementation, preferring that
the package is easily distributable on multiple operatin systems and architectures
rather than having complex dependencies.

## Roadmap

* Minimum bounding circle algorithms (Megiddo's algorithm, Welzl's algorithm)
* Circle packing
* Rectangle packing
* Knapsack packing


## Contributing

The author is an enthusiastic amateur at this class of problems, so would gladly
accept contributions.

We aim to support the [NEP29](https://numpy.org/neps/nep-0029-deprecation_policy.html) roadmap. No pull requests will be accepted that add support for older versions than these.
