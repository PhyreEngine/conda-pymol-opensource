This repository contains a [conda][conda] recipe for building the open-source
version of [PyMol][pymol], a molecular visualisation program.

This recipe will fetch the latest version of PyMol from SVN.

## Prerequisites

1. You will need an installation of [conda][miniconda].

2. Your root conda installation must have the `conda-build` installed.

3. You must have the `conda-forge` enabled.

## Building

First retrieve svn metadata by running `svn info
https://svn.code.sf.net/p/pymol/code/trunk > svninfo`. Then you should be able
to build this package by simply running `conda build .`.

[conda]: https://conda.io
[pymol]: https://sourceforge.net/projects/pymol/
[miniconda]: https://conda.io/miniconda.html
