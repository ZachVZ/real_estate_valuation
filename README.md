# real_estate_valuation

This notebook collects and analyzes housing data (price per square foot and gross rent price by neighborhood) from SFO between 2010-2016.  
Below are the four steps that will be performed in this notebook: 

1. Calculate and Plot the Average Sale Prices per Square Foot and the Avg. Gross Rent
2. Compare the Average Sale Prices by Neighborhood
3. Build an Interactive Neighborhood Map
4. Identify neighborhoods with best potential ROI


## Technologies Require
* This project leverages python version 3.8.5
* python dotenv Library
* Alpaca SDK
* Request Library
* JSON Library
* Project will be accomplished in JupyterLab


## Install python dotenv Library
* On the terminal (Git Bash) under the conda dev environment, type the code below:
pip install python-dotenv

## Install Alpaca SDK
* On the terminal (Git Bash) under the conda dev environment, type the code below:
pip install alpaca-trade-api

## Install Request Library
* On the terminal (Git Bash) under the conda dev environment, type the code below:
conda install -c anaconda requests

## Install JSON Libary
* On the terminal (Git Bash) under the conda dev environment, type the code below:
conda install -c jmcmurray json


## Installation Guide and Running Jupyter Notebook
Installing Jupyter notebook
* On the terminal (Git Bash) under the conda dev environment, type the code below:

pip install jupyterlab

* To open the Jupyter notebook
Open a new Git Bash and type the below command into your conda dev environment:

jupyter lab

* then hit the ENTER key to run



## Required Imports
* pandas - data manipulation and analysis
* Path from pathlib - import CSV files
* %matplotlib inline - assist in building plots and visuals
* hvPlot - enables interactive plotting tools such as line and bar graphs
* os - portable way of using operating system dependent functionality
* PyVizlot - Visualization package that provides a single platform for accessing multiple visualization libraries 
* json - convert the python dictionary from the API into a JSON string that can be written into a file
* from dotenv import load_dotenv - reads key-value pairs from a .env file and can set them as environment variables
* MAPBOX API - This is used to get API data for the data. The user needs to register for personal account and save their own keys
* plotly.express -  data visualization for figure generation

## Install Guide
* import os
* import pandas as pd
* import plotly.express as px
* import hvplot.pandas
* import matplotlib.pyplot as plt
* from pathlib import Path
* from dotenv import load_dotenv

## Usage
To use the JupyterLab notebook clone the repo and run git bash, open notebook san_francisco_housing.ipynb and create a new .env file that holds your MAPBOX API key

### Contributors
Zach Zwiener

### Contact
Email - zachzwiener3@gmail.com

### License
MIT