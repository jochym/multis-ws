# MULTIS Workshop - Ab Initio Methods

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jochym/multis-ws/env?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fjochym%252Fmultis-ws%26urlpath%3Dlab%252Fworkspaces%252Fmultis-ws%252Ftree%252Fmultis-ws%252F%26branch%3Dmaster)

Workshop materials for the MULTIS conference covering ab initio methods in solid state physics.
Based on materials from [abinitio-methods](https://github.com/jochym/abinitio-methods).

## Notebooks (to be added)

1. Crystal Building & Ground State Calculations
2. Phonon Dispersion Curves (Finite Displacements / DFPT)

## Environment

- Built from `env` branch: Ubuntu 24.04 base + conda packages
- ABINIT 9.8.4 (conda-forge)
- ALAMODE 1.4.2 / anphon (conda-forge + binary)
- openMPI for parallel execution
- ASE, numpy, matplotlib, scipy, jupyterlab (conda-forge)

## Launch

Click the Binder badge above to launch the interactive environment.

The environment is built from the `env` branch (config files only).
Content (notebooks, data) is pulled from `master` branch at runtime via nbgitpuller.
This way, changing notebooks does not trigger environment rebuilds.