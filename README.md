# SEAVEALite

**SEAVEALite** is a lightweight collection of tutorials, Jupyter notebooks and examples for the
[SEAVEA toolkit](https://www.seavea-project.org/), an open-source framework for Verification,
Validation and Uncertainty Quantification (VVUQ) of simulation codes.

It provides short, practical walkthroughs of the core SEAVEA components:

- **EasyVVUQ**: uncertainty quantification and sensitivity analysis
- **FabSim3**: automates simulation workflows on local machines and HPC systems
- **QCG-PilotJob**: runs large ensembles efficiently on HPC

The material is intended for new users who want to get started quickly. For the full toolkit,
including surrogate modelling and multiscale coupling, see the individual SEAVEA component repositories.

## Notebooks

| Notebook | Description |
|----------|-------------|
| [seavea-workflow.ipynb](notebooks/seavea-workflow.ipynb) | End-to-end SEAVEA workflow: FabSim3 + FabFlee Mali simulation, EasyVVUQ sensitivity analysis, and QCG-PilotJob ensembles on HPC. |

## Setup

Follow the guide for your operating system:

- [Linux](docs/setup_linux.md)
- [macOS](docs/setup_macos.md)
- [Windows (WSL2)](docs/setup_windows_wsl.md)

Then create the Python environment and Jupyter kernel from the repository root:

```bash
bash scripts/setup_notebook_env.sh
```

See [troubleshooting](docs/troubleshooting.md) if anything goes wrong.

## Layout

```
notebooks/   Jupyter notebooks
scripts/     Environment setup scripts
docs/        OS-specific setup guides and troubleshooting
examples/    Example configuration files
```
