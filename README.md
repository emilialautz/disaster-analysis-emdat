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

Delforge et al. (2025)


## em-dat.ipynb

This notebook losely follows a tutorial found on the EM-DAT GitHub (https://github.com/em-dat/python_tutorials/blob/main/python_tutorial_1_basic_operations_and_plotting.ipynb). In em-dat.ipynb, the data is loaded and analyzed with simple filtering, grouping and plotting methods.


## logistic_regression.ipynb

In this notebook, the methodology of Liu et al. (2024) is reproduced, who study flood trends and factors affecting flood-related deaths using multivariable logistic regression. Data from EM-DAT (Delforge et al., 2025) are combined with demographic data from UNdata (https://data.un.org/Data.aspx?d=POP&f=tableCode%3a1) and Our World in Data (https://ourworldindata.org/grapher/who-regions?tab=table).


## risk_assessment.ipynb 

This notebook follows the methodology of Nakasu & Amrapala (2023), who analyze 'risk' and trends of natural disasters in Southeast Asia using data from EM-DAT (Delforge et al., 2025). Specifically, impacts associates with natural disasters are compared for different disaster types.


## Notebook 4


## Sources 

Delforge, D., Wathelet, V., Below, R., Sofia, C. L., Tonnelier, M., von Loenhout, J. A. F. and Speybroeck, N. (2025). EM-DAT: the Emergency Events Database. *International Journal of Disaster Risk Reduction, 124*, 1-17. https://doi.org/10.1016/j.ijdrr.2025.105509

Liu, Q., Du, M., Wang, Y., Deng, J., Yan, W., Qin, C., Liu, M. & Liu, J. (2024). Global, regional and national trends and impacts of natural floods, 1990-2022. *Bull World Health Organ, 102*(6), 410-420. https://doi.org/10.2471/BLT.23.290243

Nakasu, T., Amrapala, C. (2023). Evidence-based disaster risk assessment in Southeast Asian countries. *Natural Hazards Research, 3*(2), 295-304. https://doi.org/10.1016/j.nhres.2023.04.001 
