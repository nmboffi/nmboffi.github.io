---
layout: page
title: code
permalink: /code/
---
Below are some pieces of open source software that I've written for research projects. I hope you'll find them useful. They're listed in reverse-chronological order for when they were written, not necessarily when they were released.

The latest code is mostly built upon neural network libraries in Python such as ``jax`` and ``PyTorch``, with intended applications in scientific computing and generative modeling. The older code is written in ``C++`` (or even ``FORTRAN``) and uses more classical techniques, such as parallel programming in ``openmp`` and ``MPI``. The focus was mostly on large-scale and high-resolution simulation of disordered systems from statistical physics and continuum mechanics.



1. [stochastic interpolants](https://github.com/malbergo/stochastic-interpolants) (with [Michael Albergo](http://malbergo.me) and [Eric Vanden Eijnden](https://wp.nyu.edu/courantinstituteofmathematicalsciences-eve2/))

1. [score-based transport modeling](https://github.com/nmboffi/sbtm) (with [Eric Vanden Eijnden](https://wp.nyu.edu/courantinstituteofmathematicalsciences-eve2/))

1. [spin glass evolutionary dynamics](https://github.com/nmboffi/spin_glass_evodyn/tree/main) (with Yipei Guo, [Chris Rycroft](https://people.math.wisc.edu/~chr/), and [Ariel Amir](https://www.weizmann.ac.il/complex/amir/))

1. [shear transformation zone++](https://github.com/nmboffi/stzpp) (with [Chris Rycroft](https://people.math.wisc.edu/~chr/))

1. [real-space Hartree-Fock](https://real-space.org) (with [Amir Natan](http://www.eng.tau.ac.il/~amirn/), note: I only contributed the Hartree-Fock implementation, not the entire package)
