# A template repo for Python projects

To use this template, click the green button at the top of the GitHib page that's cleverly called **"Use this template"**.

This template currently uses Python 3.11. But test run on 3.8 and above. It also includes:

- [pip-tools](https://pypi.org/project/pip-tools/) for dependency management.
- [pytest](https://docs.pytest.org/en/6.2.x/) for testing
- [flit](https://flit.readthedocs.io/en/latest/index.html) for building distribution files.
- GitHub Actions for continuous integration and deployment.

## Setup

To create a virtual environment and install all dependencies, run:

```shell
# On windows
> python -m venv .venv
> .venv/Scripts/Activate
> python -m pip install --upgrade pip
> python -m pip install -r requirements.txt 
```

That's it, you're all set to start coding your application!

## Build and Release

Use `flit build` to build a distribution file locally.

To release a new version, tag the commit with `v*` and push to the remote. The Github action will automatically build and upload the distribution file. Be sure to set a `PYPI_API_TOKEN` environment variable with your PyPI API token to upload to PyPi before tagging a release version.
