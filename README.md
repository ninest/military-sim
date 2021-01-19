# Military sim

## Build setup
First, install [poetry](https://python-poetry.org/docs/#installation).

Clone or fork the repository, then run

```bash
poetry install
```

To activate the virtual environment, run

```bash
poetry shell
```

Run Military sim with

```bash
python -m military-sm
```

*Note that we do not need to use `python3`. In the virtualenv, `python` refers to Python version 3.7.*

The `-m` flag runs the `military-sim` "module" as a script. This just means running `__main__.py`