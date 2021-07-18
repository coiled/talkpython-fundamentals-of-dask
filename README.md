# Fundamentals of Dask

This repository contains the material for **Talk Python Training course** on Fundamentals Dask.


## Prerequisites

- Basic Python

Not required, but nice to have:
- pandas
- NumPy
- scikit-learn
- Machine Learning
- JupyterLab
- conda (for local setup)
- Terminal (for local setup)

## Setup

You get up and running in two ways:

### Launch Binder

[![Binder](https://mybinder.org/badge_logo.svg)]()

The binder project allows you to open Jupyter notebooks in this repository in an online executable environment. Click on the "launch binder" link in your browser window to get started. It might take a few minutes to start.

*Note: Binder notebooks timeout if inactive for more than 10 mins.*

### Local setup (recommended)

* [Fork this repository](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo)

* Clone your forked repository:

```git clone http://github.com/<username>/talkpython-fundamentals-of-dask```

* From root directory:

```cd talkpython-fundamentals-of-dask```

create a new conda environment:

```conda env create -f environment.yml```

* Activate the conda environment:

``` conda activate talkpython-dask```

* Start JupyterLab

```jupyter lab```
