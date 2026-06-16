# MULTIS Workshop - Environment Configuration

This branch contains **only the environment configuration** for the MULTIS workshop.

## Files

- `environment.yml` - Conda environment (abinit, alamode, ase, numpy, matplotlib, scipy, jupyterlab)
- `apt.txt` - System packages (openmpi-bin, libopenmpi-dev)
- `requirements.txt` - Pip packages (reserved)
- `postBuild` - Runs once after build (kernel install, verification)
- `start` - Runs at each session start (PATH, env vars)

## Build

This branch is built by mybinder.org to create the Docker image.
Content (notebooks, data) is pulled from `main` branch at runtime via nbgitpuller.

## Local Development

```bash
# Build with repo2docker
repo2docker --editable .

# Or use binder locally
binder-build .
```