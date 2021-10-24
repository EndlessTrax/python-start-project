# A template repo for Python projects

To use this template, click the green button at the top of the GitHib page that's cleverly called **"Use this template"**.

This template currently uses Python 3.10. It also includes:

- [poetry](https://python-poetry.org/) for dependency management.
- [pytest](https://docs.pytest.org/en/6.2.x/) for testing
- [pre-commit](https://pre-commit.com/) hooks for:
  - [isort](https://pycqa.github.io/isort/)
  - [black](https://black.readthedocs.io/en/stable/)
  - [flake8](https://flake8.pycqa.org/en/latest/)
- GitHub Actions for continuous integration.

## Setup

You should have `poetry` installed to use this template. You can install this a number of ways if you do not currently have it. You can check out their installation instructions here: [https://python-poetry.org/docs/#installation](https://python-poetry.org/docs/#installation)

To create a virtual environment and install all dependencies including dev dependencies, run:

```shell
poetry install
```

That's it, you're all set to start coding your application!
