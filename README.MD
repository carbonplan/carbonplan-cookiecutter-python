
<p align="left" >
<a href='https://carbonplan.org'>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://carbonplan-assets.s3.amazonaws.com/monogram/light-small.png">
  <img alt="CarbonPlan monogram." height="48" src="https://carbonplan-assets.s3.amazonaws.com/monogram/dark-small.png">
</picture>
</a>
</p>

# CarbonPlan Cookiecutter Python Template

A CarbonPlan cookiecutter template for a starting a Python project.

[![CI](https://github.com/carbonplan/python-project-template/actions/workflows/main.yaml/badge.svg)](https://github.com/carbonplan/python-project-template/actions/workflows/main.yaml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


## Usage

In a virtual environment install cookiecutter:

`pip install cookiecutter`

### Template your project

After installing cookiecutter run:

`cookiecutter https://github.com/carbonplan/carbonplan-cookiecutter-python`

This should run a CLI that walks you through project templating.


### Setup your project

Todo: add instructions to:
- push your new project to github:
- enable github settings (for CI, pre-commit gh action etc)
- instructions for docs: carbonplan docs vs readme vs rtd or?
- create an environment (mamba, uv, pixi, venv etc..)
- install your your project
- run pre-commit
- run mypy


TODO: how do we use cruft to keep all projects up to date?

## Project defaults
This template uses:
- Github actions for CI
- `pre-commit` for code quality and linting
#todo- `mypy` for typing
- pytest for testing
- conda/mamba environment.yaml file if your project has difficult dependencies (GDAL, xESMF etc.)
- pyproject.toml for project information


We can modify these and add more defaults such as:
- docs (.md)
- pypi and pypi-test
- pixi or uv for env
- or others (open an issue)

## license

All the code in this repository is [MIT](https://choosealicense.com/licenses/mit/)-licensed, but we request that you please provide attribution if reusing any of our digital content (graphics, logo, articles, etc.).

## about us

CarbonPlan is a nonprofit organization that uses data and science for climate action. We aim to improve the transparency and scientific integrity of climate solutions with open data and tools. Find out more at [carbonplan.org](https://carbonplan.org/) or get in touch by [opening an issue](https://github.com/carbonplan/python-project-template/issues/new) or [sending us an email](mailto:hello@carbonplan.org).
