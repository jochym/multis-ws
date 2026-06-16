# MULTIS Workshop - Ab Initio Methods

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jochym/multis-ws/env?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fjochym%252Fmultis-ws%26urlpath%3Dlab%252Fworkspaces%252Fmultis-ws%252Ftree%252Fmultis-ws%252F%26branch%3Dmain)

Workshop materials for the MULTIS conference covering ab initio methods in solid state physics.
Based on materials from [abinitio-methods](https://github.com/jochym/abinitio-methods).

## Notebooks

- **00_Introduction.ipynb** - Workshop overview, environment check
- **notebooks/01_Building_Crystals.ipynb** - Crystal structure building with ASE
- **notebooks/02_Convergence.ipynb** - Convergence testing (ecut, k-points)
- **notebooks/03_Ground_State.ipynb** - Ground state calculations
- **notebooks/04_Phonons.ipynb** - Phonon dispersion curves (ALAMODE/anphon)

## Environment

Built from `env` branch via mybinder.org two-layer setup:

- **Environment** (`env` branch): Ubuntu 24.04 + conda packages (abinit, alamode, ase, numpy, matplotlib, scipy, jupyterlab) + openMPI
- **Content** (`main` branch): Notebooks, data files, pseudopotentials, scripts - pulled at runtime via nbgitpuller

This separation means changing notebooks does **not** trigger environment rebuilds.

## Launch

Click the Binder badge above to launch the interactive environment.