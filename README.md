library
==============================

[![stability-experimental](https://img.shields.io/badge/stability-experimental-orange.svg)](https://github.com/mkenney/software-guides/blob/master/STABILITY-BADGES.md#experimental)

This project explores the applications of LLMs. It uses "library (bibliotheca)" as the context. 


## Update Notes

<details>
  <summary> see details </summary>
- [x] Setup project structure
</details>

## How to use?
<details>
  <summary> see details </summary>

#### 1. Download this repo
```bash
git clone https://github.com/dujm/library.git
```
#### 2. Create a conda environment
```bash
# create an env with a Python version higher than Python 3.10 (here I create an env named "library" with Python 3.11)
conda env create --name library --file=environments.yml

# activate env
conda activate library
```

#### 3. Add conda environment to your jupyter lab (or jupyter notebook)

```bash
# add conda environment to jupyter lab
conda install ipykernel
ipython kernel install --user --name=library

# open jupyter lab
jupyter lab
```

#### 4. Run notebooks
 * Go to `notebooks/`
 * Open a notebook
 * Select the kernel `library`
</details>

## Project Organization
<details>
  <summary> see details </summary>

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data/
    │
    ├── docs/               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models/             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks/          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, 
    │
    ├── reports/            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │
    ├── requirements.txt   <- The requirements file for reproducing the Python environment 
    │
    ├── environment.yml    <- The environment file for reproducing the conda environment
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    ├── src/                <- Source code for use in this project.
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
</details>


---
<br>

#### [Go to Top](#TOP)

