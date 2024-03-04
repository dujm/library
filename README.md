library
==============================

[![stability-experimental](https://img.shields.io/badge/stability-experimental-orange.svg)](https://github.com/mkenney/software-guides/blob/master/STABILITY-BADGES.md#experimental)

This project explores the applications of LLMs. It uses "library (bibliotheca)" as the context. 

<details>
  <summary><h2>Update Notes</h2></summary>

 - Setup project structure



 </details> 



<details>
  <summary><h2>How to use?</h2></summary>
  
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

<details>
  <summary><h2>Project Organization</h2></summary>
    

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


--------

<p><small>Project organization based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

</details>