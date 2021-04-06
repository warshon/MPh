﻿Pythonic scripting interface for Comsol Multiphysics

[Comsol][comsol] is a commercial software application that is widely
used in science and industry for research and development. It excels
at modeling almost any (multi-)physics problem by solving the governing
set of partial differential equations via the finite-element method.
It comes with a modern graphical user interface to set up simulation
models and can be scripted from Matlab or via its native Java API.

MPh brings the dearly missing power of Python to the world of Comsol.
It leverages the universal Python-to-Java bridge provided by [JPype][jpype]
to access the native API, and wraps it in a layer of pythonic ease-of-use.
The Python wrapper covers common scripting tasks, such as loading a
model from a file, modifying parameters, importing data, to then run the
simulation and evaluate the results.

Comsol models are marked by their `.mph` file extension, which stands
for multi-physics. Hence the name of this library. It is open-source
and in no way affiliated with Comsol Inc., the company that develops
and sells the simulation software.

Find the full [documentation on Read-the-Docs][docs].

[comsol]: https://www.comsol.com
[jpype]:  https://pypi.org/project/JPype1
[docs]:   https://mph.readthedocs.io

[![citation](https://zenodo.org/badge/264718959.svg)](https://zenodo.org/badge/latestdoi/264718959)
[![license](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![source](https://img.shields.io/github/stars/John-Hennig/MPh?style=social)](https://github.com/John-Hennig/MPh)