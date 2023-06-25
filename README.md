# Week 1 MSRI python notebooks

## Environment setup instructions
Managing your virtual environments and packages is easier with conda. If you don't already have conda, please install it using [this guide](https://docs.conda.io/en/latest/miniconda.html). If you have a Windows machine, I recommend installing [Windows subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install) first and then installing conda/doing all coding work via WSL.

### Making a new conda environment
Once you have conda installed, create a new conda environment using:
`conda create --name msri`

Activate the environment:
`conda activate msri`

### Installing packages
Once you have activated your conda environment, install all required packages using the following command:
`pip install -r requirements.txt`

Make sure you add your conda environment to your jupyter notebook using:
`python -m ipykernel install --user --name=msri`

