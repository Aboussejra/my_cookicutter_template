# Python Cookiecutter Template

Generates a Python project structure with Poetry for package management and other dev tools

## Dev dependencies that are included

- black
- ruff
- isort
- mypy
- pre-commit
- pytest

## How to use

First make sure you have cookiecutter installed. Instructions can be found [here](https://cookiecutter.readthedocs.io/en/1.7.2/installation.html).

Once cookiecutter is installed go at the directory where you want to create the project and run:

```
cookiecutter https://github.com/Aboussejra/my_cookicutter_template
```

Install the dependencies

```
poetry install
```

Create a git repository

```
git init
```

Install the pre-commit hooks

```
pre-commit install
```
