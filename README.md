# Data Tooling 101 Sandbox

Welcome to a very lightweight introduction to some fun tools used by data scientists and engineers in Python, on behalf of Empathetech. This is not meant to be an exhaustive or rigorous resource, but a quick way for people not fully familiar with Python to get an early exposure to some cool tools for data science and big data use cases. We're primarily going to use Jupyter Lab to explore popular modules like Pandas and Numpy to see what we can do with CSV datasets.

There are a LOT of free resources out there outside of this, so once you've had a chance to play around with this, go out in the wild and learn more things!

## Setup

### 1. Install Python 3

Your machine may already have Python, but if you don't, here's a [pretty comprehensive installation guide](https://realpython.com/installing-python/) for Python, organized by OS.

### 2. Install and setup PDM

To make sure we don't have weird behavior caused by local v. global installation of Python packages, we're going to use PDM, a Python package and dependency manager, to handle packages and virtual environment stuff. To install it, check out [the docs here](https://pdm.fming.dev/latest/).

Once you've installed PDM, run

```bash
pdm install
```

in this repo to do the initial installation of a virtual environment, and installing modules in the `pyproject.toml` file via `pip` within that environment.

### 3. Open a Jupyter Lab instance

The pyproject.toml file and `pdm.lock` should include an installation of Jupyter Lab, but you should definitely read the docs for both this and seaborn, a visualization package that works well with dataframes, the data structure that is used by Python data scientists and data engineers to handle and transform large datasets:

- [Jupyter Lab](https://jupyter.org/try)
- [seaborn](https://seaborn.pydata.org/)

Run the following in the terminal:

```bash
jupyter-lab
```

This will spin up a localhost server for you to create and interact with Jupyter notebooks at [http://localhost:8888/lab](http://localhost:8888/lab).

## Resources

- [Jupyter Notebook Cheat Sheet](https://medium.com/edureka/jupyter-notebook-cheat-sheet-88f60d1aca7)
