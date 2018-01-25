mol2scad.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
===============
~~[![GitLab Build Status](https://gitlab.com/KOLANICH/mol2scad.py/badges/master/pipeline.svg)](https://gitlab.com/KOLANICH/mol2scad.py/pipelines/master/latest)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/mol2scad.py/badges/master/coverage.svg)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/mol2scad.py.svg)](https://libraries.io/github/KOLANICH/mol2scad.py)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

This tool converts `mol` and `sdf` files into OpenSCAD files showing a 3D model of a molecule. Either run it in this folder or copy `util.scad` to the folder with generated files. Also you will need [scad-utils](https://github.com/OskarLinde/scad-utils.git) either installed or put in the same dir.

Requirements
------------
* [`mollusk`](https://github.com/georglind/mollusk) ![License](https://img.shields.io/github/license/georglind/mollusk.svg) - `mol` (and `sdf`) file parser
* [`webcolors`](https://github.com/ubernostrum/webcolors) [![PyPi Status](https://img.shields.io/pypi/v/webcolors.svg)](https://pypi.python.org/pypi/webcolors) [![CI Build Status](https://github.com/ubernostrum/webcolors/workflows/CI/badge.svg)](https://github.com/ubernostrum/webcolors/actions?query=workflow%3ACI) ![License](https://img.shields.io/github/license/ubernostrum/webcolors.svg) - colors
* [`SolidPython`](https://github.com/SolidCode/SolidPython) [![PyPi Status](https://img.shields.io/pypi/v/plumbum.svg)](https://pypi.python.org/pypi/solid) [![CircleCI Build Status](https://circleci.com/gh/SolidCode/SolidPython.svg?style=shield)](https://circleci.com/gh/SolidCode/SolidPython) ![License](https://img.shields.io/github/license/SolidCode/SolidPython.svg) - OpenSCAD AST
* `mendeleev` [![PyPi Status](https://img.shields.io/pypi/v/mendeleev.svg)](https://pypi.org/pypi/mendeleev) - chemical elements database
* [`plumbum`](https://github.com/tomerfiliba/plumbum) [![PyPi Status](https://img.shields.io/pypi/v/plumbum.svg)](https://pypi.org/pypi/plumbum)
  [![CI Build Status](https://github.com/tomerfiliba/plumbum/workflows/CI/badge.svg)](https://github.com/tomerfiliba/plumbum/actions)
  [![Coveralls Coverage](https://coveralls.io/repos/tomerfiliba/plumbum/badge.svg?branch=master&service=github)](https://coveralls.io/github/tomerfiliba/plumbum?branch=master)
 ![License](https://img.shields.io/github/license/tomerfiliba/plumbum.svg) - for command line interface
