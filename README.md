# Discovering Disease Outbreaks Starting Repository

Starter repository for Manning PBC: Discovering and Tracking Disease Outbreaks with Data Science and Python

## Setup

This project requires Python 3.7 installed with the [anaconda distribution](https://www.anaconda.com/distribution/).

To install the required libraries in a new virtual environment, run `conda env create -f environment.yml` from the project root 
directory. This will install the  libraries into a virtual env that can be activated with `conda activate discovering-disease-outbreaks`. 

The data is located at `data/headlines.txt`. Run `jupyter notebook` to start a Jupyter Notebook and get coding!

# My personal environment

- Changed `conda` dependencies with `pipenv` ones

- A dependency is needed for installing basemap

        brew install geos
        
- To install 1.2.1 version of basemap:

        pipenv install git+https://github.com/matplotlib/basemap.git@master#egg=basemap
