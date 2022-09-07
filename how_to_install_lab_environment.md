
# Machine Learning 1 Labs

To ensure labs can be graded properly, we ask you to use the provided conda environment to run the lab notebooks in. Please install miniconda from https://conda.io/miniconda.html for your operating system (Linux or MacOS are strongly recommended), as follows.    

## Installing conda
Go to https://conda.io/miniconda.html and use the provided 64bit python 3.7 installer for your operating system.
    
### Windows
Use the anaconda prompt for the following commands

## Setting up the environment
Download the environment.yml file from Canvas, and create an environment with the command:
```
conda env create -f path/to/environment.yml
```

Removing the environment if something goes wrong
```
conda remove --name ml1labs --all
```
## Activating / Deactivating the environment
```
conda activate ml1labs

conda deactivate ml1labs
```
Windows:
```
conda activate ml1labs
conda deactivate ml1labs
```

## Starting the server:
From the folder where you have the lab files stored:
```
jupyter notebook
```
You will see a bunch of messages, along with the following:
```
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=asdf234asdfasdfsdaf
```
Open your browser and go the the link shown in your terminal. You can now navigate to the lab notebook from there on.
