library
==============================

[![stability-experimental](https://img.shields.io/badge/stability-experimental-orange.svg)](https://github.com/mkenney/software-guides/blob/master/STABILITY-BADGES.md#experimental)

This project explores the applications of LLMs. It uses a "library (bibliotheca)" as the context. 


## I. Prerequisite
<details>
  <summary> click to see details </summary>

 * Python 11
</details>

## II. How to use this repo?
<details>
  <summary> click to see details </summary>

#### 1. Download this repo
```bash
git clone https://github.com/dujm/library.git

# remove my git directory
rm -rf .git/

# create a new git repository if you need
#git init
```
#### 2. Create a conda environment (names as e.g.`library`) 
```bash
# create an env with Python 11 (see file `environments.yml`)
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

#### 4. Set up Ollama
 * Below is for MacOS. Find more instructions on [Ollama](https://github.com/ollama/ollama) if you use other operating systems.

##### a. First-time using Ollma (for Mac users)
 * [Download file from Ollama website](https://ollama.ai/download)
 * Open Ollama app
 * Select a model from [Model library](https://github.com/ollama/ollama). 
 * I selected`llama2` model. 
 * Download them in the terminal
```sh
# pull llama2 model
ollama pull llama2
```

##### b. For future use of Ollama 
 * Open Ollama app


#### 5. Run notebooks
 * Go to `notebooks/`
 * Open a notebook
 * Select the kernel `library`
</details>

## III. Project Organization
<details>
  <summary> click to see details </summary>

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data/              <- Data directory
    │
    ├── docs/              <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models/            <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks/         <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, 
    │
    ├── reports/           <- Generated analysis as HTML, PDF, LaTeX, etc.
    │
    ├── requirements.txt   <- The requirements file for reproducing the Python environment 
    │
    ├── environment.yml    <- The environment file for reproducing the conda environment
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    ├── src/               <- Source code for use in this project.
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
</details>



<br>

## Thanks to
<details>
  <summary> click to see details </summary>

 * [Project Gutenberg](https://www.gutenberg.org/)
 * [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science)
</details>


#### [Go to Top](#TOP)

