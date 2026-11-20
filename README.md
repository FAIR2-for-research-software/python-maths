# python-maths

Basic math functions in Python. This repository is used in the [Git With It][git_with_it] course.

## Working in a `uv` environment

Make sure you have [uv] installed.

### Create virtual environment

Use `uv venv` to [create and activate a virtual environment][uv_venv]
```bash
cd ~/work/git/git-with-it
uv venv --python 3.14
source .venv/bin/activate   # If on GNU/Linux or OSX
.venv\Scripts\activate      # If on M$-Windows
```

### Install the package and dependencies

```bash
uv pip install .
```

## Running tests

Make sure you have activated your virtual environment environment. Then run:

```bash
pytest
```

[git_with_it]: https://fair2-for-research-software.github.io/git-with-it/
[uv]: https://docs.astral.sh/uv/getting-started/installation/
[uv_venv]: https://docs.astral.sh/uv/pip/environments/
