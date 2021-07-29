# Fundamentals of Dask

This repository contains the material for **Talk Python Training course** on Fundamentals Dask.

The Python data science stack, consisting of tools like pandas, NumPy, scikit-learn, and many more is extremely powerful, but it rarely leverages the parallel computing potential of modern hardware. Dask can help bridge this gap. This course will teach you how to parallelize everything from array computations to general Python code with Dask and even perform distributed machine learning to train models at scale.

Take the course at: [training.talkpython.fm](https://training.talkpython.fm/courses/fundamentals-of-dask-getting-up-to-speed)

In this course, you will learn to:

* Scale array computations using a parallel alternative to NumPy
* Parallelize general Python code including for-loops
* Work with unstructured data in parallel
* Train machine learning models faster using distributed computing
* And lots more!

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

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/coiled/talkpython-fundamentals-of-dask/master?urlpath=lab/tree/03-array.ipynb)

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
