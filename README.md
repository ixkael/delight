# Delight
**Photometric redshift via Gaussian processes with physical kernels.**

*Warning: this code is still in active development and is not quite ready to be blindly applied to arbitrary photometric galaxy surveys. But this day will come.*

[![alt tag](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/ixkael/Delight/blob/master/LICENSE)
[![alt tag](https://travis-ci.org/ixkael/Delight.svg?branch=master)](https://travis-ci.org/ixkael/Delight)
[![Latest PDF](https://img.shields.io/badge/PDF-latest-orange.svg)](https://github.com/ixkael/Delight/blob/master/paper/PhotoZviaGP_paper.pdf)
[![Coverage Status](https://coveralls.io/repos/github/ixkael/Delight/badge.svg?branch=master)](https://coveralls.io/github/ixkael/Delight?branch=master)

**Tests**: pytest for unit tests, PEP8 for code style, coveralls for test coverage.

## Content

**./paper/**: journal paper describing the method </br>
**./delight/**: main code (Python/Cython) </br>
**./tests/**: test suite for the main code </br>
**./notebooks/**: demo notebooks using delight </br>
**./data/**: some useful inputs for tests/demos </br>
**./other/**: useful mathematica notebooks, etc </br>

## Requirements

Python 3.5, cython, numpy, scipy, pytest, pylint, coveralls, matplotlib, astropy </br>

## Authors

Boris Leistedt (NYU) </br>
David W. Hogg (NYU) (Flatiron)

Please cite [Leistedt and Hogg (2016)]
(https://arxiv.org/abs/1612.00847) if you use this code your
research. The BibTeX entry is:

    `@article{delight,
        author         = "Leistedt, Boris and Hogg, David W.",
        title          = "{Data-driven, interpretable photometric redshifts trained on heterogeneous and unrepresentative data}",
        year           = "2016",
        eprint         = "1612.00847",
        archivePrefix  = "arXiv",
        primaryClass   = "astro-ph.CO",
        SLACcitation   = "%%CITATION = ARXIV:1612.00847;%%"
    }`


## License

Copyright 2016-2017 the authors. The code in this repository is released under the open-source MIT License. See the file LICENSE for more details.
