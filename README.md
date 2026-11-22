# Python Intro

A collection of Python practice assignments and Jupyter notebooks covering core programming concepts, data handling, and introductory scientific computing.

## Repository contents

| File | Overview |
| --- | --- |
| [Assignment 3 notebook](assignment%203.ipynb) | Uses Pandas to reshape sample employee contact data from wide format to long format. |
| [Assignment 4 notebook](assignment%204.ipynb) | Practices dictionaries, lists, tuples, file handling, classes, dates, and calculations with 2D lists. |
| [Assignment 5 notebook](assignment%205.ipynb) | Explores NumPy and SciPy matrix operations, linear systems, eigenvalues, LU and QR decompositions, SVD, and least squares. |
| [Titanic data notebook](titanic%20file%20handle.ipynb) | Loads and cleans Titanic passenger data, filters rows, removes duplicate passenger IDs, and creates a family-size column. |

### Assignment PDF exports

- [Assignment 1 PDF](assignment%201%E2%80%A6%20-%20JupyterLab.pdf)
- [Assignment 2 PDF](assignment%202%E2%80%A6%20-%20JupyterLab.pdf)
- [Assignment 3 PDF](assignment%203%E2%80%A6%20-%20JupyterLab.pdf)

## Getting started

You need Python and JupyterLab. Install the packages used across the notebooks, then start JupyterLab:

```bash
python -m pip install pandas numpy scipy jupyterlab
jupyter lab
```

Open a notebook from the JupyterLab file browser and run its cells. You can install only the package needed for a particular notebook if you prefer:

- `pandas` for Assignment 3 and the Titanic notebook
- `numpy` and `scipy` for Assignment 5
- Assignment 4 uses Python's standard library

## Data source

The Titanic notebook reads its CSV directly from the public `datasciencedojo/datasets` GitHub repository. An internet connection is needed to run that notebook; the CSV is not stored in this repository.
