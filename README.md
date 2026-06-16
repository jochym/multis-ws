# MULTIS Workshop - Ab Initio Methods

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jochym/multis-ws/env?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fjochym%252Fmultis-ws%26branch%3Dmain%26urlpath%3Dlab)

Workshop materials for the MULTIS conference covering ab initio methods in solid state physics.
Based on materials from [abinitio-methods](https://github.com/jochym/abinitio-methods).

## Notebooks

- **00_Introduction.ipynb** - Workshop overview, environment check
- **notebooks/01_Building_Crystals.ipynb** - Crystal structure building with ASE
- **notebooks/02_Convergence.ipynb** - Convergence testing (ecut, k-points)
- **notebooks/03_Ground_State.ipynb** - Ground state calculations
- **notebooks/04_Phonons.ipynb** - Phonon dispersion curves (abinit DFPT)

## Environment

Built from `env` branch via mybinder.org two-layer setup:

- **Environment** (`env` branch): Ubuntu 24.04 + conda packages (abinit 10.0.3, ase 3.28.0, numpy 2.5, matplotlib 3.10.9, scipy 1.17.1, jupyterlab 4.5.8, nbgitpuller) + openMPI
- **Content** (`main` branch): Notebooks, data files, pseudopotentials, scripts - pulled at runtime via nbgitpuller

This separation means changing notebooks does **not** trigger environment rebuilds.

## Launch

Click the Binder badge above to launch the interactive environment.