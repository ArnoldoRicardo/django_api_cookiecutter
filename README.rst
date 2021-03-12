Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/ArnoldoRicardo/api_cookiecutter

Then:

build project

    docker-compose -f local.yml build

and run

    docker-compose -f local.yml run
