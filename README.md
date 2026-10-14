# SEAVEA Notebooks

Jupyter notebooks for the SEAVEA toolkit (FabSim3, Flee/FabFlee, EasyVVUQ, QCG-PilotJob).

## Notebooks

| Notebook | Description |
|----------|-------------|
| [seavea-tutorial.ipynb](notebooks/seavea-tutorial.ipynb) | End-to-end SEAVEA workflow: FabSim3 + FabFlee Mali simulation, EasyVVUQ sensitivity analysis, and QCG-PilotJob ensembles on HPC. |

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
