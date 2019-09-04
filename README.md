🌾 ag-residues
==============================

Code for data processing and analysis of agricultural residues as an alternate food source in catastrophic scenarios

## Setup

You will first need to obtain `libspatialindex`, which can be installed on MacOS as follows:

```brew install spatialindex```

Installation for Windows and *nix systems can be found here:
http://toblerity.org/rtree/install.html

For Python environment, and dependency management, it's recommended to use `conda`.
Download Miniconda from here: https://docs.conda.io/en/latest/miniconda.html and follow
the setup instructions for your platform.

Once installed, run the following to create a new environment and work in it (requires
a bash-like terminal)
```bash
conda create -n ag-residues python=3.7
conda activate ag-residues
```

Then, install requirements into your environment:
```bash
conda run pip install -r requirements.txt
```

You can then spawn a Jupyter Lab instance and access the notebooks in this repo:
```bash
jupyter lab
```


Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
