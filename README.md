# numproj2

This repository contains the notebooks and supporting package code for the Numerical I project.

## Requirements

- Python 3.12
- [`uv`](https://docs.astral.sh/uv/)

## Setup

Install the project and all dependencies with:

```bash
uv sync
```

This creates a local virtual environment in `.venv`.

## How To Run

The main work for this project lives in the notebooks under `problems/`.

1. Sync the environment:

```bash
uv sync
```

2. Open one of the notebooks in `problems/` in your editor, for example:

- `problems/exercise1.ipynb`
- `problems/exercise2.ipynb`
- `problems/exercise3.ipynb`
- `problems/exercise4.ipynb`
- `problems/exercise5.ipynb`

3. Select the Python interpreter from `.venv` when your editor asks for a kernel.

If you want to run Python commands from the terminal, use:

```bash
uv run python
```

For example:

```bash
uv run python -c "from numproj2 import hello; print(hello())"
```
