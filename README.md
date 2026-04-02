# Disaster Analysis with EM-DAT

This repository contains four notebooks on the analysis of natural disasters using data from EM-DAT. Each notebook reproduces the methodology of a published paper or tutorial. References and links to the original works are provided in each notebook.

## Setting up

### Windows (using conda in Anaconda Powershell prompt):
```bash
cd <project directory>

# installing environment with conda
conda env create --name emdat -f environment.yml

# activate emdat
conda activate emdat

# to leave emdat
conda deactivate

# to delete emdat
conda env remove --name emdat
```

### MacOS and Linux (with python=python3)

```bash
# create local environment emdat
python -m venv emdat

# activate emdat
source emdat/bin/activate

# install packages
pip install --upgrade pip
pip install -r requirements.txt

# to leave emdat
deactivate

# to delete emdat
rm -rf emdat
```

## Data

## em-dat.ipynb

This notebook losely follows a tutorial found on the EM-DAT GitHub (https://github.com/em-dat/python_tutorials/blob/main/python_tutorial_1_basic_operations_and_plotting.ipynb). In em-dat.ipynb, the data is loaded and analyzed with simple filtering, grouping and plotting methods.


## Notebook 2

## Notebook 3

## Notebook 4

