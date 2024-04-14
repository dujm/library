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
#### 2. Create a conda environment (named as e.g.`library`) 
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
 * Download it in the terminal
```sh
# pull llama2 model
ollama pull llama2
```

##### b. For future use of Ollama 
 * Open Ollama app
 * Or run the bash script in the terminal

```sh
bash scripts/ollama_serve.sh

# if you want to stop Ollma in the Mac terminal 
pkill ollama
```


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

#### A
 * [Agentchat RetrieveChat](https://github.com/microsoft/autogen/blob/main/notebook/agentchat_RetrieveChat.ipynb)
 * [Autogen ollama](https://github.com/ScottLL/autogen-ollama/blob/main/entrypoint.sh)
 * [Chromadb](https://realpython.com/chromadb-vector-database/)
 * [Langroid](https://github.com/langroid/langroid)
 * [Two Agent Debates with Tools](https://github.com/langchain-ai/langchain/blob/master/cookbook/two_agent_debate_tools.ipynb)
 * [LangChain AI Image Recognition](https://github.com/sugarforever/LangChain-Tutorials/blob/main/LangChain_AI_Image_Recognition.ipynb)


#### B
 * [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science)
 * [Project Gutenberg](https://www.gutenberg.org/)
 * [GIFs For Readme](https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/blob/main/README.md)


<br>

<img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d899-44b4-b1d9-4eeccf656e44.gif" width="500">
<br><br>

</details>

#### [Top](#TOP)

