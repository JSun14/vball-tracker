# vball-tracker

## Getting Started
Currently only supporting macOS development

Going to use Poetry as our virtual environment and package dependency manager. It's robust, user-friendly, popular, and powerful if we need it to be.
```
python3 -m pip install poetry
cd {insert path to repo parent directory}
git clone git@github.com:JSun14/vball-tracker.git
cd vball-tracker
poetry install
```
- poetry basic commands ([docs page](https://python-poetry.org/docs/cli/)):
    - poetry shell: activates the sub-shell for the virtual environment when you are in the vball-tracker folder
    - poetry install: either creates or follows an existing pyproject.toml + poetry.lock file in downloading / updating packages.
        - poetry install --sync: run this on every branch checkout or pull (will automate this at some point), think it's just a lighterweight command for sync'ing purposes only
    - exit (or control d on mac): exits sub-shell for the virtual environment
    - poetry add "pypi package name": not only installs the package via pip, but also adds it to the pyproject.toml + poetry lock so that everyone else can get the new package you're adding
    - poetry remove "package name": likewise removes it

## Objectives
What do we want to accomplish with this system?

Key Features:
- key feature one
- key feature two
