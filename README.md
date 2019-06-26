# Improvements to Consumption Prediction

These Jupyter Notebooks contain a portion of the associated code to the paper *Improvements to Consumption Prediction: Machine Learning Methods and Novel Features*. 

* Economic variable stationarity:  pce_econ_stat.ipynb 
* Sentiment variable stationarity:  pce_sent_stat.ipynb
* Vector Autoregression (VAR) models:  pce_var_model.ipynb
* Random Forest models:  pce_rf_model.ipynb

## Requirements

Python 3.*
	
Anaconda Python distribution (recommended)
	
Additional Python packages (included with Anaconda distribution)
    -jupyter
    -matplotlib
    -numpy
    -pandas
    -seaborn
    -sklearn
    -statsmodels 

## Installation

### 1. Install Anaconda

Reference:  
 	macOS:    https://docs.continuum.io/anaconda/install/mac-os.html  
 	Windows:  https://docs.continuum.io/anaconda/install/windows  

### 2. Create conda environment from the pce-requirements.yml file

Reference: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

Example Code:  `conda env create -f pce-requirements.yml --name impr-pce-env`

### 3. Activate the new environment

Example Code:  
	macOS: `conda activate impr-pce-env`  
 	Windows: `activate impr-pce-env`  

### 4. Launch Jupyter Notebooks

Reference: https://jupyter-notebook.readthedocs.io/en/stable/

Example Code:  `jupyter notebook`